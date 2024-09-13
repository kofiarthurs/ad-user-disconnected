<h1>Active Directory - User Falls From Domain</h1>
<h2>Description</h2>
When I try to sign in with my helpdesk which has admin privileges, I get this error. When I sign in as Jess (regular user), there is no problem meaning Jess’s account is saved locally on the machine.
</br>
</br>

<img src="https://imgur.com/K2JdWht.png" height="80%" width="80%"/>

We can’t ping Desktop-2 (Jess's machine) and the network isn’t connected. The firewall has already been setup to receive pings.
</br>

<img src="https://imgur.com/dtkafcn.png" height="80%" width="80%"/>

We will first try to sign out and back in. This didn’t work, I’ll need to sign in using the local admin account and rejoin the domain.
</br>

<img src="https://imgur.com/VXGsIcJ.png" height="80%" width="80%"/>

After disconnecting, I’ll need to come back to this page to reconnect to the domain, using the domain admin account.
</br>

<img src="https://imgur.com/8J7P1Zb.png" height="80%" width="80%"/>

Success!
</br>

<img src="https://imgur.com/ZNkEcWR.png" height="80%" width="80%"/>
