# Chess (C# • WPF)

A local **two-player chess** game written in C# with a WPF/XAML UI.  
All chess rules are implemented in a separate logic library.

## Features
- Standard chess setup & legal move validation
- **Special moves:** castling, en passant, pawn promotion, double pawn move
- **Special Rules:** insufficient material, 50 move rule, threefold repetition
- Turn indicators and game end detection (checkmate/stalemate)
- Simple, clean UI built with WPF

## Requirements
- Windows
- Visual Studio 2022+ **or** .NET SDK 6.0+ (if using .NET Core WPF)
- (If the project targets .NET Framework, open with Visual Studio)

## Build & Run

### Option A — Visual Studio (recommended)
1. Open `Chess.sln`.
2. Set **ChessUI** as the startup project.
3. Press **F5** to build & run.

### Option B — .NET CLI (if `ChessUI` targets .NET Core WPF)
```bash
git clone https://github.com/justas0221/Chess.git
cd Chess/ChessUI
dotnet run
