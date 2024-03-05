# tbDEX iOS Example App

An example iOS application that communicates with the [tbdex-pfi-examplar](https://github.com/TBD54566975/tbdex-pfi-exemplar).

## Setup

### Step 1: Update `Config.swift`

There are two values that are generated by the `tbdex-pfi-exemplar` application which must be set in the `Config.swift` file in order to properly communicate with the PFI:
1. `pfiDIDURI` - Set this to the "PFI DID FROM SERVER" value that is output to the console when running the `npm run server` command.
2. `claim` - Set this to the signed credential that is output to the console when running the `npm run example-issue-credential` command.

### Step 2: Open Xcode

Open `tbDEX-Example.xcodeproj` in Xcode. All package dependencies, including `web5-swift` and `tbdex-swift` should be downloaded automatically. If they are not, select `File > Packages > Resolve Package Versions` from the menu.

### Step 3: Run the App

Click the play button on the upper left of the Xcode sidebar, or select `Product > Run` from the menu.
