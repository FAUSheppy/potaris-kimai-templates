# Deploy

    # <start the container> #
    docker exec kimai_kimai_1 mkdir /opt/kimai/var/invoices/
    docker cp invoice-potaris.html.twig kimai_kimai_1:/opt/kimai/var/invoices/
    docker exec kimai_kimai_1 chown www-data:www-data -R /opt/kimai/var/invoices/

