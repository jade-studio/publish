# Jade Studio publish

Shared GitHub Actions workflow that publishes a repo's static files (HTML/CSS/JS/images/video) to jadestudiohub.com.
It signs in with GitHub's OIDC identity token instead of stored secrets, and the jade-publisher Worker decides what each repo may write.
