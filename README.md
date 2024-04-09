# Notes



## Cron with 1 minute loop, with time zone in java  
private static final String TIME_ZONE = "America/Sao_Paulo";  
@Scheduled(cron = "0 * * * * *", zone = TIME_ZONE)  
