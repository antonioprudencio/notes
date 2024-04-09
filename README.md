# notes



## Cron with 1 minute loop, with time zone
private static final String TIME_ZONE = "America/Sao_Paulo";
@Scheduled(cron = "0 * * * * *", zone = TIME_ZONE)
