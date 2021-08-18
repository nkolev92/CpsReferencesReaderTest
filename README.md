# Sample Repo for CpsReferencesReader

This is a sample repo with 2 csproj PackageReference projects and 1 native project.

MainApplication -> NativeProject -> LeafLibrary.

The purpose of this setup is to flow the dependencies from LeafLibrary to MainApplication, which is why a lock file exists.

To run the test case:

1. Load CpsReferencesReaderTest.sln
2. Run a restore - no errors should happen.
3. Run a build - ignore any build warnings, they are not relevant to the scenario.