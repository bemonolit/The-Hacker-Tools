# Table of contents

* [Introduction](README.md)
* [Mimikatz 🥝](mimikatz/README.md)
  * [General 🛠️](mimikatz/general.md)
  * [Modules](mimikatz/modules/README.md)
    * [crypto](mimikatz/modules/crypto/README.md)
      * [capi](mimikatz/modules/crypto/capi.md)
      * [certificates](mimikatz/modules/crypto/certificates.md)
      * [certtohw](mimikatz/modules/crypto/certtohw.md)
      * [cng](mimikatz/modules/crypto/cng.md)
      * [extract](mimikatz/modules/crypto/extract.md)
      * [hash](mimikatz/modules/crypto/hash.md)
      * [keys](mimikatz/modules/crypto/keys.md)
      * [kutil 🛠️](mimikatz/modules/crypto/kutil.md)
      * [providers](mimikatz/modules/crypto/providers.md)
      * [sc](mimikatz/modules/crypto/sc.md)
      * [scauth 🛠️](mimikatz/modules/crypto/scauth.md)
      * [stores](mimikatz/modules/crypto/stores.md)
      * [system](mimikatz/modules/crypto/system.md)
      * [tpminfo](mimikatz/modules/crypto/tpminfo.md)
    * [dpapi](mimikatz/modules/dpapi/README.md)
      * [blob](mimikatz/modules/dpapi/blob.md)
      * [cache](mimikatz/modules/dpapi/cache.md)
      * [capi](mimikatz/modules/dpapi/capi.md)
      * [chrome](mimikatz/modules/dpapi/chrome.md)
      * [cloudapkd 🛠️](mimikatz/modules/dpapi/cloudapkd.md)
      * [cloudapreg](mimikatz/modules/dpapi/cloudapreg.md)
      * [cng](mimikatz/modules/dpapi/cng.md)
      * [create 🛠️](mimikatz/modules/dpapi/create.md)
      * [cred](mimikatz/modules/dpapi/cred.md)
      * [credhist](mimikatz/modules/dpapi/credhist.md)
      * [luna](mimikatz/modules/dpapi/luna.md)
      * [masterkey](mimikatz/modules/dpapi/masterkey.md)
      * [protect](mimikatz/modules/dpapi/protect.md)
      * [ps](mimikatz/modules/dpapi/ps.md)
      * [rdg](mimikatz/modules/dpapi/rdg.md)
      * [sccm](mimikatz/modules/dpapi/sccm.md)
      * [ssh](mimikatz/modules/dpapi/ssh.md)
      * [tpm](mimikatz/modules/dpapi/tpm.md)
      * [vault](mimikatz/modules/dpapi/vault.md)
      * [wifi](mimikatz/modules/dpapi/wifi.md)
      * [wwan](mimikatz/modules/dpapi/wwan.md)
    * [event](mimikatz/modules/event/README.md)
      * [clear](mimikatz/modules/event/clear.md)
      * [drop](mimikatz/modules/event/drop.md)
    * [kerberos](mimikatz/modules/kerberos/README.md)
      * [ask](mimikatz/modules/kerberos/ask.md)
      * [clist](mimikatz/modules/kerberos/clist.md)
      * [golden](mimikatz/modules/kerberos/golden.md)
      * [hash](mimikatz/modules/kerberos/hash.md)
      * [list](mimikatz/modules/kerberos/list.md)
      * [ptc](mimikatz/modules/kerberos/ptc.md)
      * [ptt](mimikatz/modules/kerberos/ptt.md)
      * [purge](mimikatz/modules/kerberos/purge.md)
      * [tgt](mimikatz/modules/kerberos/tgt.md)
    * [lsadump](mimikatz/modules/lsadump/README.md)
      * [backupkeys](mimikatz/modules/lsadump/backupkeys.md)
      * [cache](mimikatz/modules/lsadump/cache.md)
      * [changentlm](mimikatz/modules/lsadump/changentlm.md)
      * [dcshadow](mimikatz/modules/lsadump/dcshadow.md)
      * [dcsync](mimikatz/modules/lsadump/dcsync.md)
      * [mbc](mimikatz/modules/lsadump/mbc.md)
      * [netsync](mimikatz/modules/lsadump/netsync.md)
      * [lsa](mimikatz/modules/lsadump/lsa.md)
      * [packages](mimikatz/modules/lsadump/packages.md)
      * [postzerologon](mimikatz/modules/lsadump/postzerologon.md)
      * [rpdata](mimikatz/modules/lsadump/rpdata.md)
      * [sam](mimikatz/modules/lsadump/sam.md)
      * [secrets](mimikatz/modules/lsadump/secrets.md)
      * [setntlm](mimikatz/modules/lsadump/setntlm.md)
      * [trust](mimikatz/modules/lsadump/trust.md)
      * [zerologon](mimikatz/modules/lsadump/zerologon.md)
    * [misc](mimikatz/modules/misc.md)
      * [aadcookie](mimikatz/modules/misc/aadcookie.md)
      * [clip](mimikatz/modules/misc/clip.md)
      * [compress](mimikatz/modules/misc/compress.md)
      * [cmd](mimikatz/modules/misc/cmd.md)
      * [detours](mimikatz/modules/misc/detours.md)
      * [easyntlmchall](mimikatz/modules/misc/easyntlmchall.md)
      * [efs](mimikatz/modules/misc/efs.md)
      * [lock](mimikatz/modules/misc/lock.md)
      * [memssp](mimikatz/modules/misc/memssp.md)
      * [mflt](mimikatz/modules/misc/mflt.md)
      * [ncroutemon](mimikatz/modules/misc/ncroutemon.md)
      * [ngcsign](mimikatz/modules/misc/ngcsign.md)
      * [printnightmare](mimikatz/modules/misc/printnightmare.md)
      * [regedit](mimikatz/modules/misc/regedit.md)
      * [sccm](mimikatz/modules/misc/sccm.md)
      * [shadowcopies](mimikatz/modules/misc/shadowcopies.md)
      * [skeleton](mimikatz/modules/misc/skeleton.md)
      * [spooler](mimikatz/modules/misc/spooler.md)
      * [taskmgr](mimikatz/modules/misc/taskmgr.md)
      * [wp](mimikatz/modules/misc/wp.md)
      * [xor](mimikatz/modules/misc/xor.md)
    * [net](mimikatz/modules/net/README.md)
      * [alias](mimikatz/modules/net/alias.md)
      * [deleg](mimikatz/modules/net/deleg.md)
      * [group](mimikatz/modules/net/group.md)
      * [if](mimikatz/modules/net/if.md)
      * [serverinfo](mimikatz/modules/net/serverinfo.md)
      * [session](mimikatz/modules/net/session.md)
      * [share](mimikatz/modules/net/share.md)
      * [stats](mimikatz/modules/net/stats.md)
      * [tod](mimikatz/modules/net/tod.md)
      * [trust](mimikatz/modules/net/trust.md)
      * [user](mimikatz/modules/net/user.md)
      * [wsession](mimikatz/modules/net/wsession.md)
    * [privilege](mimikatz/modules/privilege/README.md)
      * [backup](mimikatz/modules/privilege/backup.md)
      * [debug](mimikatz/modules/privilege/debug.md)
      * [driver](mimikatz/modules/privilege/driver.md)
      * [id](mimikatz/modules/privilege/id.md)
      * [name](mimikatz/modules/privilege/name.md)
      * [restore](mimikatz/modules/privilege/restore.md)
      * [security](mimikatz/modules/privilege/security.md)
      * [sysenv](mimikatz/modules/privilege/sysenv.md)
      * [tcb](mimikatz/modules/privilege/tcb.md)
    * [process](mimikatz/modules/process/README.md)
      * [exports](mimikatz/modules/process/exports.md)
      * [imports](mimikatz/modules/process/imports.md)
      * [list](mimikatz/modules/process/list.md)
      * [resume](mimikatz/modules/process/resume.md)
      * [run](mimikatz/modules/process/run.md)
      * [runp](mimikatz/modules/process/runp.md)
      * [start](mimikatz/modules/process/start.md)
      * [stop](mimikatz/modules/process/stop.md)
      * [suspend](mimikatz/modules/process/suspend.md)
    * [rpc](mimikatz/modules/rpc/README.md)
      * [close](mimikatz/modules/rpc/close.md)
      * [connect](mimikatz/modules/rpc/connect.md)
      * [enum](mimikatz/modules/rpc/enum.md)
      * [server](mimikatz/modules/rpc/server.md)
    * [sekurlsa](mimikatz/modules/sekurlsa/README.md)
      * [backupkeys](mimikatz/modules/sekurlsa/backupkeys.md)
      * [bootkey](mimikatz/modules/sekurlsa/bootkey.md)
      * [cloudap](mimikatz/modules/sekurlsa/cloudap.md)
      * [credman](mimikatz/modules/sekurlsa/credman.md)
      * [dpapi](mimikatz/modules/sekurlsa/dpapi.md)
      * [dpapisystem](mimikatz/modules/sekurlsa/dpapisystem.md)
      * [ekeys](mimikatz/modules/sekurlsa/ekeys.md)
      * [kerberos](mimikatz/modules/sekurlsa/kerberos.md)
      * [krbtgt](mimikatz/modules/sekurlsa/krbtgt.md)
      * [livessp](mimikatz/modules/sekurlsa/livessp.md)
      * [logonpasswords](mimikatz/modules/sekurlsa/logonpasswords.md)
      * [minidump](mimikatz/modules/sekurlsa/minidump.md)
      * [msv](mimikatz/modules/sekurlsa/msv.md)
      * [process](mimikatz/modules/sekurlsa/process.md)
      * [pth](mimikatz/modules/sekurlsa/pth.md)
      * [ssp](mimikatz/modules/sekurlsa/ssp.md)
      * [tickets](mimikatz/modules/sekurlsa/tickets.md)
      * [trust](mimikatz/modules/sekurlsa/trust.md)
      * [tspkg](mimikatz/modules/sekurlsa/tspkg.md)
      * [wdigest](mimikatz/modules/sekurlsa/wdigest.md)
    * [service](mimikatz/modules/service/README.md)
      * [-](mimikatz/modules/service/undefined.md)
      * [+](mimikatz/modules/service/+.md)
      * [preshutdown](mimikatz/modules/service/preshutdown.md)
      * [remove](mimikatz/modules/service/remove.md)
      * [resume](mimikatz/modules/service/resume.md)
      * [shutdown](mimikatz/modules/service/shutdown.md)
      * [start](mimikatz/modules/service/start.md)
      * [stop](mimikatz/modules/service/stop.md)
      * [suspend](mimikatz/modules/service/suspend.md)
    * [sid](mimikatz/modules/sid/README.md)
      * [add](mimikatz/modules/sid/add.md)
      * [clear](mimikatz/modules/sid/clear.md)
      * [lookup](mimikatz/modules/sid/lookup.md)
      * [modify](mimikatz/modules/sid/modify.md)
      * [patch](mimikatz/modules/sid/patch.md)
      * [query](mimikatz/modules/sid/query.md)
    * [standard](mimikatz/modules/standard/README.md)
      * [answer](mimikatz/modules/standard/answer.md)
      * [base64](mimikatz/modules/standard/base64.md)
      * [cd](mimikatz/modules/standard/cd.md)
      * [cls](mimikatz/modules/standard/cls.md)
      * [coffee](mimikatz/modules/standard/coffee.md)
      * [exit](mimikatz/modules/standard/exit.md)
      * [hostname](mimikatz/modules/standard/hostname.md)
      * [localtime](mimikatz/modules/standard/localtime.md)
      * [log](mimikatz/modules/standard/log.md)
      * [sleep](mimikatz/modules/standard/sleep.md)
      * [version](mimikatz/modules/standard/version.md)
    * [token](mimikatz/modules/token/README.md)
      * [elevate](mimikatz/modules/token/elevate.md)
      * [list](mimikatz/modules/token/list.md)
      * [revert](mimikatz/modules/token/revert.md)
      * [run](mimikatz/modules/token/run.md)
      * [whoami](mimikatz/modules/token/whoami.md)
    * [ts](mimikatz/modules/ts/README.md)
      * [logonpasswords](mimikatz/modules/ts/logonpasswords.md)
      * [mstsc](mimikatz/modules/ts/mstsc.md)
      * [multirdp](mimikatz/modules/ts/multirdp.md)
      * [remote](mimikatz/modules/ts/remote.md)
      * [sessions](mimikatz/modules/ts/sessions.md)
    * [vault](mimikatz/modules/vault/README.md)
      * [cred](mimikatz/modules/vault/cred.md)
      * [list](mimikatz/modules/vault/list.md)
* [🛠️ Impacket](impacket/README.md)
  * [Library](impacket/library/README.md)
    * [SMB](impacket/library/smb.md)
    * [LDAP](impacket/library/ldap.md)
    * [MSRPC](impacket/library/msrpc.md)
    * [NTLM](impacket/library/ntlm.md)
    * [Kerberos](impacket/library/kerberos.md)
  * [Script examples](impacket/examples/README.md)
    * [addcomputer.py](impacket/examples/addcomputer.py.md)
    * [atexec.py](impacket/examples/atexec.py.md)
    * [dcomexec.py](impacket/examples/dcomexec.py.md)
    * [dpapi.py](impacket/examples/dpapi.py.md)
    * [esentutl.py](impacket/examples/esentutl.py.md)
    * [exchanger.py](impacket/examples/exchanger.py.md)
    * [findDelegation.py](impacket/examples/finddelegation.py.md)
    * [GetADUsers.py](impacket/examples/getadusers.py.md)
    * [getArch.py](impacket/examples/getarch.py.md)
    * [Get-GPPPassword.py](impacket/examples/get-gpppassword.py.md)
    * [GetNPUsers.py](impacket/examples/getnpusers.py.md)
    * [getPac.py](impacket/examples/getpac.py.md)
    * [getST.py](impacket/examples/getst.py.md)
    * [getTGT.py](impacket/examples/gettgt.py.md)
    * [GetUserSPNs.py](impacket/examples/getuserspns.py.md)
    * [goldenPac.py](impacket/examples/goldenpac.py.md)
    * [karmaSMB.py](impacket/examples/karmasmb.py.md)
    * [kintercept.py](impacket/examples/kintercept.py.md)
    * [lookupsid.py](impacket/examples/lookupsid.py.md)
    * [mimikatz.py](impacket/examples/mimikatz.py.md)
    * [mqtt\_check.py](impacket/examples/mqtt\_check.py.md)
    * [mssqlclient.py](impacket/examples/mssqlclient.py.md)
    * [mssqlinstance.py](impacket/examples/mssqlinstance.py.md)
    * [netview.py](impacket/examples/netview.py.md)
    * [nmapAnswerMachine.py](impacket/examples/nmapanswermachine.py.md)
    * [ntfs-read.py](impacket/examples/ntfs-read.py.md)
    * [ntlmrelayx.py](impacket/examples/ntlmrelayx.py.md)
    * [ping.py](impacket/examples/ping.py.md)
    * [ping6.py](impacket/examples/ping6.py.md)
    * [psexec.py](impacket/examples/psexec.py.md)
    * [raiseChild.py](impacket/examples/raisechild.py.md)
    * [rdp\_check.py](impacket/examples/rdp\_check.py.md)
    * [reg.py](impacket/examples/reg.py.md)
    * [registry-read.py](impacket/examples/registry-read.py.md)
    * [rpcdump.py](impacket/examples/rpcdump.py.md)
    * [rpcmap.py](impacket/examples/rpcmap.py.md)
    * [sambaPipe.py](impacket/examples/sambapipe.py.md)
    * [samrdump.py](impacket/examples/samrdump.py.md)
    * [secretsdump.py](impacket/examples/secretsdump.py.md)
    * [services.py](impacket/examples/services.py.md)
    * [smbclient.py](impacket/examples/smbclient.py.md)
    * [smbexec.py](impacket/examples/smbexec.py.md)
    * [smbpasswd.py](impacket/examples/smbpasswd.py.md)
    * [smbrelayx.py](impacket/examples/smbrelayx.py.md)
    * [smbserver.py](impacket/examples/smbserver.py.md)
    * [sniff.py](impacket/examples/sniff.py.md)
    * [sniffer.py](impacket/examples/sniffer.py.md)
    * [split.py](impacket/examples/split.py.md)
    * [ticketConverter.py](impacket/examples/ticketconverter.py.md)
    * [ticketer.py](impacket/examples/ticketer.py.md)
    * [wmiexec.py](impacket/examples/wmiexec.py.md)
    * [wmipersist.py](impacket/examples/wmipersist.py.md)
    * [wmiquery.py](impacket/examples/wmiquery.py.md)
* [🛠️ CrackMapExec 🔱](crackmapexec/README.md)
  * [General](crackmapexec/general.md)
  * [Protocols](crackmapexec/protocols/README.md)
    * [mssql](crackmapexec/protocols/mssql.md)
    * [ssh](crackmapexec/protocols/ssh.md)
    * [winrm](crackmapexec/protocols/winrm.md)
    * [ldap](crackmapexec/protocols/ldap.md)
    * [smb](crackmapexec/protocols/smb.md)
  * [Modules](crackmapexec/modules.md)
