### Release Goal
 
A release goal to migrate all projects to Storyboard has been proposed for the Rocky release. There has been much discussion around this patch and the majority of opinions land on a desire to migrate away from Launchpad in favor of Storyboard, but concern over feasibility to migrate all projects in a single release. There’s an interest in migrating one or two larger projects as case studies for the rest of the projects. Currently the Storyboard team is working on testing larger projects finding good candidates to be these case studies.  
 
### Private Stories 

Work on private stories to accommodate the needs of the Vulnerability Management Team and other projects that utilize private bug reporting has been progressing and is getting close to being completed. The API for hiding private stories and support for ‘teams’ to be able to view stories had already been implemented. Patches for support to properly populate worklist items into automatic worklists and to allow permissions to be set for teams in worklists and boards are among the last items that need to be implemented for private stories to be supported [1][2]. The last large blocker for private stories is providing a safe way for people to report bugs privately and subscribe to the correct team which is also currently in progress[3]. 

### Migrations

At this point we have migrated a number of projects over already even though the goal has not been officially accepted for the next release. Working to create a tipping point, the Storyboard team has been test migrating a variety of projects and reaching out to ptls who’s projects would be good candidates. That being said, if you haven’t been contacted and are interested in migrating, directions on how to run a test migration can be found here [4].

  
##### Projects (or repos) Migrated Storyboard:

  

- Octavia 
- Craton 
- Cloudkitty 
- Refstack 
- Monasca 
- Kolla-Kubernetes 
- ptgbot 
- contributor-guide 
- interop-wg 
  
##### Other OpenStack Projects using Storyboard

- Infra 
- Enterprise WG 
- Self Healing SIG 
  
In addition to this list, there are a number of unofficial OpenStack projects and other outside organizations that deploy and use Storyboard as their task tracker.  

### Call for Eyes and Call for Help

The number one barrier to migration at this point is that people aren’t up to date on the actual capabilities of Storyboard. Please take a few minutes to go and play around with the dev environment[5]. You will see how far it has come since the last discussion about using it as an alternative to Launchpad. If there is something you feel is missing, please make a story for it in either the webclient project[6] or Storyboard itself[7]. 

Even better would be to get involved. We have weekly meetings Wednesday at 19:00 UTC in #openstack-meeting. If you can’t make it to a meeting come ask us questions in the #storyboard channel- we love visitors :) If you have some spare time and see something that you want to fix, we would love the help! We are a small but determined team at this point and would love some more help from you all. 
 
Sincerely, 
*The Storyboard Team*

[1] [https://review.openstack.org/#/c/307712/](https://review.openstack.org/#/c/307712/)
[2] [https://review.openstack.org/#/c/370312/](https://review.openstack.org/#/c/370312/)
[3] [https://review.openstack.org/#/c/526219](https://review.openstack.org/#/c/526219)
[4] [https://docs.openstack.org/infra/storyboard/migration.html](https://docs.openstack.org/infra/storyboard/migration.html)
[5] [https://storyboard-dev.openstack.org/#!/page/about](https://storyboard-dev.openstack.org/#!/page/about)
[6] [https://storyboard.openstack.org/#!/project/457](https://storyboard.openstack.org/#!/project/457)

[7] [https://storyboard.openstack.org/#!/project/456](https://storyboard.openstack.org/#!/project/456)