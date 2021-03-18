# Maven Java App Tutorial (Big Data 44517) - Matteo Antunez
Professor: Dr. Dennis Case
## Creating the Cloud Repo
In creating the cloud repo, there aren't that many different things you need to do or make sure are correct.

1. Ensure your repo is titled maven-java-project (exactly)
2. Ensure to add a ``` README.md ``` and ``` .gitignore ``` files
3. For ``` .gitignore ```, ensure you select Maven

Ensure that you clone your repository to your device before proceeding with this tutorial.

## Choosing a Package Name
When creating a project with maven, the user will be prompted to enter a 'groupID' which is your package name. This will create a 'outline' to your file. See example below of example names.

> edu.nwmissouri.last.first
> state.county.city.zip

## Use Maven to Draft a Project (Use temp folder)
When creating our java app, we will be using a temp folder and moving specific folders over to our cloud repository.

> Example: ``` C:\temp ```

To begin creating the draft, open your temp folder, right click, and select *Open PowerShell as Administrator*

In PowerShell, enter the following commands:

```PowerShell
> mvn archetype:generate
> [Choose Number] (or) [Enter for Default]
> [Enter for Default] [^1]
> [Enter groupID]
> [Enter repo name]
> [Enter for Default]
> [Enter for Default]
> [Enter 'Y' to Confirm]
```

[^1]: Test Footntoe