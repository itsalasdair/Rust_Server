# Oxide Permissions

oxide.grant user <name><permission>	            Grants a user a permission
oxide.revoke user <name><permission>	          Revokes a users permission
oxide.grant group <group><permission>	          Grants a group a permission
oxide.revoke group <group><permission>	        Revokes a groups permission
oxide.usergroup add <name><group>	              Adds a user to a group
oxide.usergroup remove <name><group>	          Removes a user from a group
oxide.group add <group> <"[Title]"><rank>	      Creates a new group Title and rank are optional depending on the circumstance.
oxide.group remove <group>	                    Removes a group
oxide.group set <group><"[Title]"><rank>	      Sets the title or rank of a group.
oxide.group parent <parentgroup><childgroup>	  Setting the parent group of another group
oxide.show user <name>	                        Shows a user's permissions
oxide.show group <group>	                      Shows a group's members and permissions
oxide.show perm <permission> 	                  Shows which user or group has a permission
oxide.show groups/perms	                        Shows all groups or permissions
oxide.grant group <group> *	                    Grants a group a wildcard. Wildcard simply means all. So this would grant the right to all permissions
oxide.grant user oxide.*	                      Grants a user all permissions without adding them to the admin group.
