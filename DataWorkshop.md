# Data Workshop

Get in groups of 3-4. Sign up on Google BigQuery. You can use 1TB of queries quota for free each month.
[Big Query -- Github Data Set](https://cloudplatform.googleblog.com/2016/06/GitHub-on-BigQuery-analyze-all-the-open-source-code.html)

### 1) Most frequent type of programming language?

```sql
 SELECT LAST(SPLIT(files.path, '.')) as filename
 FROM [bigquery-public-data:github_repos.sample_files] files
 LIMIT 10
```

Can you extend this to get top 10?

### 2) Top 10 Popular Imports?

```sql
SELECT line, count(*) as n
FROM (
 SELECT SPLIT(contents.content, '\n') as line
 FROM [bigquery-public-data:github_repos.sample_contents] contents
 HAVING LEFT(line, 7) = 'import '
)
GROUP BY line
ORDER BY n DESC
LIMIT 10
```

### 3) Tabs vs. Spaces?

Count the number of spaces at the start of a project.

```
SELECT count(*) as n
FROM (
 -- split each line of code into a new row
 SELECT SPLIT(contents.content, '\n') as line
 FROM [bigquery-public-data:github_repos.sample_contents] contents
 -- count spaces
 HAVING REGEXP_MATCH(line, r'^[ ]+')
)
```

Can you extend it to count for tabs, too?

##### Extend to only Javascript projects:

Can you run only for Javascript projects?
```
 -- only for Javascript
 JOIN (SELECT repo_name FROM [bigquery-public-data:github_repos.languages] 
 WHERE language.name='JavaScript') filtered_languages
 ON filtered_languages.repo_name= contents.sample_repo_name
```

### 4) Free-Style Competition

Try to come up with an interesting query to complete by end of the class. We will have groups discuss there results and query and give best prize at end.
