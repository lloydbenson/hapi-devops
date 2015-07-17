To get upstart to work:

Assuming app.conf (where app can be any name)

1.  vi app.conf and fill out and update appropriately depending on env
2.  sudo cp app.conf /etc/init (assuming thats where upstart wants stuff)
3.  sudo start app (to start)
4.  sudo stop app (to stop)
