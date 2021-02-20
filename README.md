# k8s_multinode_cluster_setup

We are integrating AWS,ANSIBLE and KUBERNETES

 ᴀɴꜱɪʙʟᴇ ʀᴏʟᴇ ᴛᴏ ᴄᴏɴꜰɪɢᴜʀᴇ ᴋ8ꜱ ᴍᴜʟᴛɪ ɴᴏᴅᴇ ᴄʟᴜꜱᴛᴇʀ ᴏᴠᴇʀ ᴀᴡꜱ ᴄʟᴏᴜᴅ.

🔅 ᴄʀᴇᴀᴛᴇ ᴀɴꜱɪʙʟᴇ ᴩʟᴀyʙᴏᴏᴋ ᴛᴏ ʟᴀᴜɴᴄʜ 3 ᴀᴡꜱ ᴇᴄ2 ɪɴꜱᴛᴀɴᴄᴇ
🔅 ᴄʀᴇᴀᴛᴇ ᴀɴꜱɪʙʟᴇ ᴩʟᴀyʙᴏᴏᴋ ᴛᴏ ᴄᴏɴꜰɪɢᴜʀᴇ ᴅᴏᴄᴋᴇʀ ᴏᴠᴇʀ ᴛʜᴏꜱᴇ ɪɴꜱᴛᴀɴᴄᴇꜱ.
🔅 ᴄʀᴇᴀᴛᴇ ᴩʟᴀyʙᴏᴏᴋ ᴛᴏ ᴄᴏɴꜰɪɢᴜʀᴇ ᴋ8ꜱ ᴍᴀꜱᴛᴇʀ, ᴋ8ꜱ ᴡᴏʀᴋᴇʀ ɴᴏᴅᴇꜱ ᴏɴ ᴛʜᴇ ᴀbᴏᴠᴇ ᴄʀᴇᴀᴛᴇᴅ ᴇᴄ2 ɪɴꜱᴛᴀɴᴄᴇꜱ ᴜꜱɪɴɢ ᴋᴜʙᴇᴀᴅᴍ.
🔅 ᴄᴏɴᴠᴇʀᴛ ᴩʟᴀyʙᴏᴏᴋ ɪɴᴛᴏ ʀᴏʟᴇꜱ ᴀɴᴅ ᴜᴩʟᴏᴀᴅ ᴛʜᴏꜱᴇ ʀᴏʟᴇ

So for doing this I have created three ansible roles : ec2_instance, master_node, worker_node

Prerequisite is that we should know how to export AWS access key and secret key.

