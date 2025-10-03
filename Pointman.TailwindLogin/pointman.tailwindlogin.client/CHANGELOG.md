This file explains how Visual Studio created the project.

The following tools were used to generate this project:
- create-vite

The following steps were used to generate this project:
- Create react project with create-vite: `npm init --yes vite@latest pointman.tailwindlogin.client -- --template=react-ts`.
- Create project file (`pointman.tailwindlogin.client.esproj`).
- Create `launch.json` to enable debugging.
- Create `nuget.config` to specify location of the JavaScript Project System SDK (which is used in the first line in `pointman.tailwindlogin.client.esproj`).
- Add project to solution.
- Update proxy endpoint to be the backend server endpoint.
- Add project to the startup projects list.
- Write this file.
