## WordPress+Nginx+PHP-FPM Deployment

Configuration the WordPress blogging platform and CMS, frontend by the Nginx web server and the PHP-FPM process manager. To use, copy the `hosts.example` file to `hosts` and edit the `hosts` inventory file to include the names or URLs of the servers you want to deploy.

Run the playbook by using below commond:

$ ansible-playbook -i hosts site.yml

The playbooks will configure MySQL, WordPress, Nginx, and PHP-FPM. When the run
is complete, you can hit access server to begin the WordPress configuration.

