#### Following enhancements have been made to the GitHub connector in version 2.0.0:

	- Added three new actions
   - `Get Repository`
   - `Get Commit`
   - `Get Commit Comparison`

- Updated `clone_repository` action
   Introduces a refactored version of the clone_repository function, aimed at improving code quality, reliability, maintainability, and operational safety. The core functionality remains the same (i.e., cloning GitHub repositories via a ZIP archive), but several important internal improvements have been made.

- Updated `push_repository` action
   - push_repository is a feature-complete, safer, and cleaner implementation that adds robust GitHub repo synchronization, supports deletion of remote files, and improves developer experience through better logging, path handling, and error management.

- Added new Pluggable source control actions in sample collection
   - `GitHub - Get Commit`
   - `GitHub - Get Commit Comparison`
   - `GitHub - Get Pull Request`
   - `GitHub - Get Repository`