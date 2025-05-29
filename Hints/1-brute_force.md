for ($i=1; $i -le 10; $i++) {
    net use \\127.0.0.1\IPC$ /user:FakeUser WrongPassword
}
<!--Run in powershell-->