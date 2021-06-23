![example workflow](https://github.com/mitchazj/template-dotnet-core-cli-csharp/actions/workflows/dotnet.yml/badge.svg)

## Introduction

Template for quickly creating a new .NET Core console application on GitPod.

## How it was generated

1. Templated with `dotnet new console` in the terminal
2. Namespace set to `dotnetcore` via editor
3. Setup `.gitignore` for sanity and `.gitpod.yml` files for GitPod
4. GitHub actions setup for building and running tests (incl. badge above)

Note that this was originally forked from https://github.com/gitpod-io/template-dotnet-core-cli-csharp and many of these were already in this template.

This repo is probably the cleanest base to work with for a new console project using GitHub, GitPod, and GitHub Actions.

## What to do after you use this template

1. Change the namespace in `dotnetcore.csproj` and in `Program.cs`
2. Change the URL in the badge in `README.md` to match your new repo URL
3. Good to go! Have fun.

## Maintenance
1. Clone the repo
2. Delete `Program.cs` and `dotnetcore.csproj`
3. Regenerate with `dotnet new console`
4. Modify as needed to match output
5. Check that the .gitignore, .gitpod.yml, and GitHub Action are still up-to-date.

<br />

\-- Mitchell Johnson
