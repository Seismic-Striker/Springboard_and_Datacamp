The two included files (accounts.csv and streams.csv) contain a sample data very similar to what we work with on a regular basis.   

accounts.csv contains information about an account, including account_number (global identifier for the account), the price the customer paid for their subscription, and whether they churned during the period of interest.  

streams.csv contains information about streams that a customer has watched during the period of interest.   The columns inculde 
account_number - global identifier for the account holder
start_timestamp - start timestamp of the stream in milli-seconds from 1.1.1970 UTC
end_timestamp - end timestamp of the stream in in milli-seconds from 1.1.1970 UTC
mos_score - a quality of experience score for the stream that takes into account things like buffering and bitrate.
