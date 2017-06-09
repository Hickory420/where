# where
Random functions that I find useful

## Note

Some functions are specific to my environment and therefore will not be of use to anyone else.

```
  Help:

     where [ -b | -c | -d | -h | -m | -n | -s | -v | -w ]

   -b | --backup    Check the backup status for a failure.
   -c | --cores     Shows information about the cores on the processor.
   -d | --dstat     Runs a dstat on the system.
   -h | --help      This help/usage message.
   -i | --ipaddress Get all ip addresses on this box.
   -l | --load      Shows the average system load.
   -m | --mail      Gives information on the mail queue of the system.
   -n | --node      Get the sitecode of the server.
   -r | --remote    Parse SSH logs to check who tried to/has logged in.
   -s | --space     The space and usage info of all partitions.
   -v | --version   The version of the script and exit.
   -w | --warning   Only show partitions in the warning range without host info.

  Example: You may also use multiple arguments at once.
  where -s -i -b -l
```
