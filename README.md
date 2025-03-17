# maven packages publishing

Edit the distribution Management element of the pom.xml file located in your package directory, replacing OWNER with the name of the personal account or organization that owns the repository and REPOSITORY with the name of the repository containing your project.

https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-apache-maven-registry

Create a GitHub token to run the workflow with only Write and Read access.

create a Repository secret and add that to GITHUB_TOKEN: ${{ secrets.JAVA_TOKEN }}

Create a .github/Workflows/publish-java-maven.yml file.


