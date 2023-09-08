# Architecture

                  geo balancer
                /      |        \          
    UAE server   CA server    general server        backup server


# steps to test
1) use ngrok and vpn to get ip of UAE, CA, or other country
2) geo balancer will redirect your request appropriate local server