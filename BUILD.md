# Building the GD Requests Geode Mod

## Prerequisites

1. **Geometry Dash** installed on your PC
2. **Geode** installed ([geode-sdk.org](https://geode-sdk.org))
3. **CMake** 3.21+ — download from cmake.org
4. **Visual Studio 2022** (or Build Tools for Visual Studio 2022)
   - During install, select: **Desktop development with C++**
5. **Geode CLI** — run in PowerShell:
   ```
   winget install GeodeSdk.GeodeCLI
   ```

## Setup (one-time)

After installing the Geode CLI, set up the SDK:

```powershell
geode sdk install
geode sdk update
```

This sets the `GEODE_SDK` environment variable automatically.

## Build

Open a **Developer PowerShell for VS 2022** (search in Start menu), then:

```powershell
cd C:\Users\Compa\gd-requests-mod

cmake -B build -A Win32
cmake --build build --config RelWithDebInfo
```

The output `.geode` file will be at:
```
build/RelWithDebInfo/xcompassionate.gd-requests.geode
```

## Install locally

Drag the `.geode` file into your GD mods folder, usually:
```
C:\Users\<you>\AppData\Local\GeometryDash\geodes\
```

Then launch GD. The mod will appear under the Geode mods list.

## Configure

1. In GD, open the Geode menu (bottom-right icon)
2. Find **GD Requests** → click the gear/settings icon
3. Paste your **Creator Token** from `gdrequests.org/bot-setup`
4. Close settings — a **Req** button now appears on the main menu

## Usage

- Click **Req** on the GD main menu to open your request queue
- Click any entry to search for that level in GD
- If the queue is empty, it shows "Queue is empty!"
