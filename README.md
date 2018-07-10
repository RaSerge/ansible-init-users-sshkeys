This role initialize your host to work with The Infrustructure.

It does 3 general tasks:

1) Configure sshd to work only with user keys and improve connection security. Use tag 'config'.
2) Add current user and their keys to the host. Use tag 'add_users'.
3) Remove fired users(only from passwd). Use tag 'remove_users'.

Define ```init_force: true``` to be implemented