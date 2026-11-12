
# Industrial UI Editor & Runtime

**A custom-built desktop UI editor and configuration-driven runtime for industrial monitoring systems.**

A real-world software engineering project developed with **VB.NET, .NET 10, Windows Forms, and MariaDB**.

The system consists of two interconnected desktop applications that separate visual interface design from runtime execution.

Instead of hardcoding individual screens, users can visually create and configure interfaces, while a separate application dynamically reconstructs and executes them using stored configurations.

## Core Features

**Visual Editor**
- Custom interactive canvas with draggable and configurable UI components
- Multi-selection, alignment, snapping, and element manipulation
- Logical coordinate system with adaptive scaling
- Dynamic property editing and configurable component behavior
- Page navigation, data bindings, and reusable element templates
- Local drafts, configuration management, and publishing workflow

**Runtime Engine**
- Dynamic UI generation from database-stored configurations
- Component reconstruction, navigation, and event handling
- Asynchronous data retrieval and periodic value updates
- Protection against outdated asynchronous refresh results
- External signal integration through native DLL interoperability
- Interactive time-series visualization with zooming, panning, and caching

## Engineering Highlights

| Area | Implementation |
|------|----------------|
| UI Engineering | Custom visual editor, drag interactions, selection management, coordinate transformations |
| Architecture | Separation of editing, persistence, and runtime rendering |
| Concurrency | Async/Await, non-blocking data retrieval, refresh state management |
| Data Layer | MariaDB, ODBC, configuration persistence, signal bindings |
| Interoperability | Managed-to-native integration using P/Invoke |
| Visualization | Custom chart rendering, historical data processing, interactive navigation |
| Workflow | Local drafts, controlled publishing, page work-status tracking |

## Tech Stack

`VB.NET` · `.NET 10` · `Windows Forms` · `MariaDB` · `ODBC` · `P/Invoke` · `Async/Await` · `GDI+`

## Demo

Short demonstrations of the visual editor and runtime application using a test interface.

### Visual Editor

Creating, positioning, and configuring UI components through the custom visual editor.

https://github.com/user-attachments/assets/f52a2665-4d8f-4df6-8cb8-8674df1a834c

### Runtime Viewer

Dynamic reconstruction and display of the configured interface in a separate runtime application.

https://github.com/user-attachments/assets/ac00a3c4-877f-4833-8a1f-ef4728b6d9c5


## Project Information

**Category:** Industrial Desktop Software  
**Platform:** Windows  
**Development:** Real-world software engineering project

Developed as part of the modernization of an existing industrial monitoring system.

The project demonstrates practical experience in desktop application architecture, custom UI engineering, asynchronous data processing, database integration, and dynamic interface rendering.

This repository is intended exclusively as a technical portfolio case study.

The source code, executable binaries, production configurations, and internal infrastructure details are not publicly distributed.
