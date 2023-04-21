Start-Sleep -Seconds 2

$wshell = New-Object -ComObject wscript.shell
for ($i = 1; $i -le 500; $i++)
{
    echo $i
    [System.Windows.Forms.SendKeys]::SendWait([char]32)
    Start-Sleep -Milliseconds 150                      
}
echo "done"
                          
