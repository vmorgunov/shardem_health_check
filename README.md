# shardem_health_check

tmux new-session -d -s shardeum_healthcheck 'bash <(curl -s https://raw.githubusercontent.com/vmorgunov/shardem_health_check/main/health.sh)'
