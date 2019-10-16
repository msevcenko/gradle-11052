# gradle-11052

This is an example for the issue report https://github.com/gradle/gradle/issues/11052

Steps to reproduce:

```
gradle -Prepo.url=https://your.repo.com -Prepo.user=your.username -Prepo.password=your-password uploadArchives
