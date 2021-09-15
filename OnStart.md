// PowerApps Bootstrap by John Paulo Mataac //
// -----------------------------------------//

// Initialize Core Settings and Variables
Concurrent(
    Set(AppTitle, "SPA Request App"),
    Set(AppVersion, "0.3.0.5"),

    // Configurations:
    Set(_isDebugMode, false),
    Set(_appID, "7f928efd-446d-46d4-9c8f-e37bcb7ffddb"),

    ...
);

// Initialize Message Constants
Concurrent(
    Set(FONT_COLOR_Title, DarkBlue),
    Set(FONT_COLOR_Normal, Gray),
    Set(MSG_CREATE_POLICY_REQUEST, ""),
    Set(MSG_APPROVE_POLICY_REQUEST_L1, ""),
    Set(MSG_APPROVE_POLICY_REQUEST_L2, "")
);

// Deep Link