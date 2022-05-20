#NetworkSettings

    AuthServer
        Description: IP of the authorization server.
        Default: 127.0.0.1

    AuthServerPort
        Description: Port of the authorization server to connect to.
        Default: 7075

    WorldServer
        Description: IP of the world server.
        Default: 127.0.0.1

    WorldServerPort
        Description: Port of the world server to connect to.
        Default: 7070

    MaxMessageSize
        Description: Maximum size of the packets the client can receive.
        Default: 16384

    SendTimeout
        Description: Amount of time a socket will wait for a send operation to complete successfully.
        Default: 5000

#InGameDebugSettings

    IsUIEnabled
        Description: Shows/Hides the HUD elements(in-world UI's like nameplates are not hidden).
        Default: true

    IsCharacterVisible
        Description: Shows/Hides your character(currently not working).
        Default: true

    ChatInputCharacterLimit
        Description: Limit the number of characters you can enter into the chat input field.
        Default: 255

    AccountID
        Description: When set and not going through the login, is used to determine which account/character you enter the world with(when set to 0 does nothing, expects you have a character).
        Default: 0
        
    Hash
        Description: Hash used for account verification.
        Default: "hash"
        
    CharacterID
        Description: ID of the character you want to log in with. Needs to be a character with an AccountID matching the AccountID set in the config.
        Default: 0
