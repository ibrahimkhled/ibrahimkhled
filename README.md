People wishing to submit BIPs, first should propose their idea or document to the [https://groups.google.com/g/bitcoindev bitcoindev@googlegroups.com] mailing list (do <em>not</em> assign a number - read <a href="bip-0002.mediawiki">BIP 2</a> for the full process). After discussion, please open a PR. After copy-editing and acceptance, it will be published here.

We are fairly liberal with approving BIPs, and try not to be too involved in decision making on behalf of the community. The exception is in very rare cases of dispute resolution when a decision is contentious and cannot be agreed upon. In those cases, the conservative option will always be preferred.

Having a BIP here does not make it a formally accepted standard until its status becomes Final or Active.

Those proposing changes should consider that ultimately consent may rest with the consensus of the Bitcoin users (see also: [https://en.bitcoin.it/wiki/Economic_majority economic majority]).

{| class="wikitable sortable" style="width: auto; text-align: center; font-size: smaller; table-layout: fixed;"
!Number
!Layer
!Title
!Owner
!Type
!Status
|- style="background-color: #ffcfcf"
| [[bip-0001.mediawiki|1]]
|
| BIP Purpose and Guidelines
| Amir Taaki
| Process
| Replaced
|- style="background-color: #cfffcf"
| [[bip-0002.mediawiki|2]]
|
| BIP process, revised
| Luke Dashjr
| Process
| Active
|-
| [[bip-0008.mediawiki|8]]
|
| Version bits with lock-in by height
| Shaolin Fry, Luke Dashjr
| Informational
| Draft
|- style="background-color: #cfffcf"
| [[bip-0009.mediawiki|9]]
|
| Version bits with timeout and delay
| Pieter Wuille, Peter Todd, Greg Maxwell, Rusty Russell
| Informational
| Final
|- style="background-color: #ffcfcf"
| [[bip-0010.mediawiki|10]]
| Applications
| Multi-Sig Transaction Distribution
| Alan Reiner
| Informational
| Withdrawn
|- style="background-color: #cfffcf"
| [[bip-0011.mediawiki|11]]
| Applications
| M-of-N Standard Transactions
| Gavin Andresen
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0012.mediawiki|12]]
| Consensus (soft fork)
| OP_EVAL
| Gavin Andresen
| Standard
| Withdrawn
|- style="background-color: #cfffcf"
| [[bip-0013.mediawiki|13]]
| Applications
| Address Format for pay-to-script-hash
| Gavin Andresen
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0014.mediawiki|14]]
| Peer Services
| Protocol Version and User Agent
| Amir Taaki, Patrick Strateman
| Standard
| Final
|-
| [[bip-0015.mediawiki|15]]
| Applications
| Aliases
| Amir Taaki
| Standard
| Deferred
|- style="background-color: #cfffcf"
| [[bip-0016.mediawiki|16]]
| Consensus (soft fork)
| Pay to Script Hash
| Gavin Andresen
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0017.mediawiki|17]]
| Consensus (soft fork)
| OP_CHECKHASHVERIFY (CHV)
| Luke Dashjr
| Standard
| Withdrawn
|- style="background-color: #ffffcf"
| [[bip-0018.mediawiki|18]]
| Consensus (soft fork)
| hashScriptCheck
| Luke Dashjr
| Standard
| Proposed
|- style="background-color: #ffcfcf"
| [[bip-0019.mediawiki|19]]
| Applications
| M-of-N Standard Transactions (Low SigOp)
| Luke Dashjr
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0020.mediawiki|20]]
| Applications
| URI Scheme
| Luke Dashjr
| Standard
| Replaced
|- style="background-color: #cfffcf"
| [[bip-0021.mediawiki|21]]
| Applications
| URI Scheme
| Nils Schneider, Matt Corallo
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0022.mediawiki|22]]
| API/RPC
| getblocktemplate - Fundamentals
| Luke Dashjr
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0023.mediawiki|23]]
| API/RPC
| getblocktemplate - Pooled Mining
| Luke Dashjr
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0030.mediawiki|30]]
| Consensus (soft fork)
| Duplicate transactions
| Pieter Wuille
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0031.mediawiki|31]]
| Peer Services
| Pong message
| Mike Hearn
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0032.mediawiki|32]]
| Applications
| Hierarchical Deterministic Wallets
| Pieter Wuille
| Informational
| Final
|- style="background-color: #ffcfcf"
| [[bip-0033.mediawiki|33]]
| Peer Services
| Stratized Nodes
| Amir Taaki
| Standard
| Rejected
|- style="background-color: #cfffcf"
| [[bip-0034.mediawiki|34]]
| Consensus (soft fork)
| Block v2, Height in Coinbase
| Gavin Andresen
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0035.mediawiki|35]]
| Peer Services
| mempool message
| Jeff Garzik
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0036.mediawiki|36]]
| Peer Services
| Custom Services
| Stefan Thomas
| Standard
| Rejected
|- style="background-color: #cfffcf"
| [[bip-0037.mediawiki|37]]
| Peer Services
| Connection Bloom filtering
| Mike Hearn, Matt Corallo
| Standard
| Final
|-
| [[bip-0038.mediawiki|38]]
| Applications
| Passphrase-protected private key
| Mike Caldwell, Aaron Voisine
| Standard
| Draft
|- style="background-color: #ffffcf"
| [[bip-0039.mediawiki|39]]
| Applications
| Mnemonic code for generating deterministic keys
| Marek Palatinus, Pavol Rusnak, Aaron Voisine, Sean Bowe
| Standard
| Proposed
|-
| 40
| API/RPC
| Stratum wire protocol
| Marek Palatinus
| Standard
| BIP number allocated
|-
| 41
| API/RPC
| Stratum mining protocol
| Marek Palatinus
| Standard
| BIP number allocated
|- style="background-color: #cfffcf"
| [[bip-0042.mediawiki|42]]
| Consensus (soft fork)
| A finite monetary supply for Bitcoin
| Pieter Wuille
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0043.mediawiki|43]]
| Applications
| Purpose Field for Deterministic Wallets
| Marek Palatinus, Pavol Rusnak
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0044.mediawiki|44]]
| Applications
| Multi-Account Hierarchy for Deterministic Wallets
| Marek Palatinus, Pavol Rusnak
| Standard
| Final
|- style="background-color: #ffffcf"
| [[bip-0045.mediawiki|45]]
| Applications
| Structure for Deterministic P2SH Multisignature Wallets
| Manuel Araoz, Ryan X. Charles, Matias Alejo Garcia
| Standard
| Proposed
|- style="background-color: #cfffcf"
| [[bip-0047.mediawiki|47]]
| Applications
| Reusable Payment Codes for Hierarchical Deterministic Wallets
| Justus Ranvier
| Informational
| Final
|- style="background-color: #ffffcf"
| [[bip-0048.mediawiki|48]]
| Applications
| Multi-Script Hierarchy for Multi-Sig Wallets
| Fontaine
| Standard
| Proposed
|- style="background-color: #cfffcf"
| [[bip-0049.mediawiki|49]]
| Applications
| Derivation scheme for P2WPKH-nested-in-P2SH based accounts
| Daniel Weigl
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0050.mediawiki|50]]
|
| March 2013 Chain Fork Post-Mortem
| Gavin Andresen
| Informational
| Final
|-
| [[bip-0052.mediawiki|52]]
| Consensus (hard fork)
| Durable, Low Energy Bitcoin PoW
| Michael Dubrovsky, Bogdan Penkovsky
| Standard
| Draft
<!-- 50 series reserved for a group of post-mortems -->
|-
| [[bip-0060.mediawiki|60]]
| Peer Services
| Fixed Length "version" Message (Relay-Transactions Field)
| Amir Taaki
| Standard
| Draft
|- style="background-color: #cfffcf"
| [[bip-0061.mediawiki|61]]
| Peer Services
| Reject P2P message
| Gavin Andresen
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0062.mediawiki|62]]
| Consensus (soft fork)
| Dealing with malleability
| Pieter Wuille
| Standard
| Withdrawn
|-
| 63
| Applications
| Stealth Addresses
| Peter Todd
| Standard
| BIP number allocated
|- style="background-color: #ffcfcf"
| [[bip-0064.mediawiki|64]]
| Peer Services
| getutxo message
| Mike Hearn
| Standard
| Obsolete
|- style="background-color: #cfffcf"
| [[bip-0065.mediawiki|65]]
| Consensus (soft fork)
| OP_CHECKLOCKTIMEVERIFY
| Peter Todd
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0066.mediawiki|66]]
| Consensus (soft fork)
| Strict DER signatures
| Pieter Wuille
| Standard
| Final
|- style="background-color: #ffffcf"
| [[bip-0067.mediawiki|67]]
| Applications
| Deterministic Pay-to-script-hash multi-signature addresses through public key sorting
| Thomas Kerin, Jean-Pierre Rupp, Ruben de Vries
| Standard
| Proposed
|- style="background-color: #cfffcf"
| [[bip-0068.mediawiki|68]]
| Consensus (soft fork)
| Relative lock-time using consensus-enforced sequence numbers
| Mark Friedenbach, BtcDrak, Nicolas Dorier, kinoshitajona
| Standard
| Final
|- style="background-color: #ffffcf"
| [[bip-0069.mediawiki|69]]
| Applications
| Lexicographical Indexing of Transaction Inputs and Outputs
| Kristov Atlas
| Informational
| Proposed
|- style="background-color: #cfffcf"
| [[bip-0070.mediawiki|70]]
| Applications
| Payment Protocol
| Gavin Andresen, Mike Hearn
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0071.mediawiki|71]]
| Applications
| Payment Protocol MIME types
| Gavin Andresen
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0072.mediawiki|72]]
| Applications
| bitcoin: uri extensions for Payment Protocol
| Gavin Andresen
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0073.mediawiki|73]]
| Applications
| Use "Accept" header for response type negotiation with Payment Request URLs
| Stephen Pair
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0074.mediawiki|74]]
| Applications
| Allow zero value OP_RETURN in Payment Protocol
| Toby Padilla
| Standard
| Rejected
|- style="background-color: #cfffcf"
| [[bip-0075.mediawiki|75]]
| Applications
| Out of Band Address Exchange using Payment Protocol Encryption
| Justin Newton, Matt David, Aaron Voisine, James MacWhyte
| Standard
| Final
|-
| [[bip-0078.mediawiki|78]]
| Applications
| A Simple Payjoin Proposal
| Nicolas Dorier
| Standard
| Draft
|- style="background-color: #ffcfcf"
| [[bip-0079.mediawiki|79]]
| Applications
| Bustapay :: a practical coinjoin protocol
| Ryan Havar
| Informational
| Replaced
|-
| [[bip-0080.mediawiki|80]]
|
| Hierarchy for Non-Colored Voting Pool Deterministic Multisig Wallets
| Justus Ranvier, Jimmy Song
| Informational
| Deferred
|-
| [[bip-0081.mediawiki|81]]
|
| Hierarchy for Colored Voting Pool Deterministic Multisig Wallets
| Justus Ranvier, Jimmy Song
| Informational
| Deferred
|- style="background-color: #ffcfcf"
| [[bip-0083.mediawiki|83]]
| Applications
| Dynamic Hierarchical Deterministic Key Trees
| Eric Lombrozo
| Standard
| Rejected
|- style="background-color: #cfffcf"
| [[bip-0084.mediawiki|84]]
| Applications
| Derivation scheme for P2WPKH based accounts
| Pavol Rusnak
| Standard
| Final
|-
| [[bip-0085.mediawiki|85]]
| Applications
| Deterministic Entropy From BIP32 Keychains
| Ethan Kosakovsky
| Informational
| Draft
|-
| [[bip-0086.mediawiki|86]]
| Applications
| Key Derivation for Single Key P2TR Outputs
| Ava Chow
| Standard
| Draft
|- style="background-color: #ffffcf"
| [[bip-0087.mediawiki|87]]
| Applications
| Hierarchy for Deterministic Multisig Wallets
| Robert Spigler
| Standard
| Proposed
|- style="background-color: #ffffcf"
| [[bip-0088.mediawiki|88]]
| Applications
| Hierarchical Deterministic Path Templates
| Dmitry Petukhov
| Informational
| Proposed
|- style="background-color: #cfffcf"
| [[bip-0090.mediawiki|90]]
|
| Buried Deployments
| Suhas Daftuar
| Informational
| Final
|- style="background-color: #cfffcf"
| [[bip-0091.mediawiki|91]]
| Consensus (soft fork)
| Reduced threshold Segwit MASF
| James Hilliard
| Standard
| Final
|-
| [[bip-0093.mediawiki|93]]
| Applications
| codex32: Checksummed SSSS-aware BIP32 seeds
| Leon Olsson Curr, Pearlwort Sneed, Andrew Poelstra
| Informational
| Draft
|-
| [[bip-0098.mediawiki|98]]
| Consensus (soft fork)
| Fast Merkle Trees
| Mark Friedenbach, Kalle Alm, BtcDrak
| Standard
| Draft
|- style="background-color: #ffcfcf"
| [[bip-0099.mediawiki|99]]
|
| Motivation and deployment of consensus rule changes ([soft/hard]forks)
| Jorge Timón
| Informational
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0100.mediawiki|100]]
| Consensus (hard fork)
| Dynamic maximum block size by miner vote
| Jeff Garzik, Tom Harding, Dagur Valberg Johannsson
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0101.mediawiki|101]]
| Consensus (hard fork)
| Increase maximum block size
| Gavin Andresen
| Standard
| Withdrawn
|- style="background-color: #ffcfcf"
| [[bip-0102.mediawiki|102]]
| Consensus (hard fork)
| Block size increase to 2MB
| Jeff Garzik
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0103.mediawiki|103]]
| Consensus (hard fork)
| Block size following technological growth
| Pieter Wuille
| Standard
| Withdrawn
|- style="background-color: #ffcfcf"
| [[bip-0104.mediawiki|104]]
| Consensus (hard fork)
| 'Block75' - Max block size like difficulty
| t.khan
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0105.mediawiki|105]]
| Consensus (hard fork)
| Consensus based block size retargeting algorithm
| BtcDrak
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0106.mediawiki|106]]
| Consensus (hard fork)
| Dynamically Controlled Bitcoin Block Size Max Cap
| Upal Chakraborty
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0107.mediawiki|107]]
| Consensus (hard fork)
| Dynamic limit on the block size
| Washington Y. Sanchez
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0109.mediawiki|109]]
| Consensus (hard fork)
| Two million byte size limit with sigop and sighash limits
| Gavin Andresen
| Standard
| Rejected
|- style="background-color: #ffffcf"
| [[bip-0111.mediawiki|111]]
| Peer Services
| NODE_BLOOM service bit
| Matt Corallo, Peter Todd
| Standard
| Proposed
|- style="background-color: #cfffcf"
| [[bip-0112.mediawiki|112]]
| Consensus (soft fork)
| CHECKSEQUENCEVERIFY
| BtcDrak, Mark Friedenbach, Eric Lombrozo
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0113.mediawiki|113]]
| Consensus (soft fork)
| Median time-past as endpoint for lock-time calculations
| Thomas Kerin, Mark Friedenbach
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0114.mediawiki|114]]
| Consensus (soft fork)
| Merkelized Abstract Syntax Tree
| Johnson Lau
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0115.mediawiki|115]]
| Consensus (soft fork)
| Generic anti-replay protection using Script
| Luke Dashjr
| Standard
| Rejected
|-
| [[bip-0116.mediawiki|116]]
| Consensus (soft fork)
| MERKLEBRANCHVERIFY
| Mark Friedenbach, Kalle Alm, BtcDrak
| Standard
| Draft
|-
| [[bip-0117.mediawiki|117]]
| Consensus (soft fork)
| Tail Call Execution Semantics
| Mark Friedenbach, Kalle Alm, BtcDrak
| Standard
| Draft
|-
| [[bip-0118.mediawiki|118]]
| Consensus (soft fork)
| SIGHASH_ANYPREVOUT for Taproot Scripts
| Christian Decker, Anthony Towns
| Standard
| Draft
|-
| [[bip-0119.mediawiki|119]]
| Consensus (soft fork)
| CHECKTEMPLATEVERIFY
| Jeremy Rubin, James O'Beirne
| Standard
| Draft
|- style="background-color: #ffcfcf"
| [[bip-0120.mediawiki|120]]
| Applications
| Proof of Payment
| Kalle Rosenbaum
| Standard
| Withdrawn
|- style="background-color: #ffcfcf"
| [[bip-0121.mediawiki|121]]
| Applications
| Proof of Payment URI scheme
| Kalle Rosenbaum
| Standard
| Withdrawn
|-
| [[bip-0122.mediawiki|122]]
| Applications
| URI scheme for Blockchain references / exploration
| Marco Pontello
| Standard
| Draft
|- style="background-color: #cfffcf"
| [[bip-0123.mediawiki|123]]
|
| BIP Classification
| Eric Lombrozo
| Process
| Active
|- style="background-color: #ffcfcf"
| [[bip-0124.mediawiki|124]]
| Applications
| Hierarchical Deterministic Script Templates
| Eric Lombrozo, William Swanson
| Informational
| Rejected
|- style="background-color: #ffffcf"
| [[bip-0125.mediawiki|125]]
| Applications
| Opt-in Full Replace-by-Fee Signaling
| David A. Harding, Peter Todd
| Standard
| Proposed
|-
| [[bip-0126.mediawiki|126]]
|
| Best Practices for Heterogeneous Input Script Transactions
| Kristov Atlas
| Informational
| Draft
|-
| [[bip-0127.mediawiki|127]]
| Applications
| Simple Proof-of-Reserves Transactions
| Steven Roose
| Standard
| Draft
|- style="background-color: #ffffcf"
| [[bip-0129.mediawiki|129]]
| Applications
| Bitcoin Secure Multisig Setup (BSMS)
| Hugo Nguyen, Peter Gray, Marko Bencun, Aaron Chen, Rodolfo Novak
| Standard
| Proposed
|- style="background-color: #ffffcf"
| [[bip-0130.mediawiki|130]]
| Peer Services
| sendheaders message
| Suhas Daftuar
| Standard
| Proposed
|- style="background-color: #ffcfcf"
| [[bip-0131.mediawiki|131]]
| Consensus (hard fork)
| "Coalescing Transaction" Specification (wildcard inputs)
| Chris Priest
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0132.mediawiki|132]]
|
| Committee-based BIP Acceptance Process
| Andy Chase
| Process
| Withdrawn
|- style="background-color: #cfffcf"
| [[bip-0133.mediawiki|133]]
| Peer Services
| feefilter message
| Alex Morcos
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0134.mediawiki|134]]
| Consensus (hard fork)
| Flexible Transactions
| Tom Zander
| Standard
| Rejected
|- style="background-color: #ffcfcf"
| [[bip-0135.mediawiki|135]]
|
| Generalized version bits voting
| Sancho Panza
| Informational
| Rejected
|-
| [[bip-0136.mediawiki|136]]
| Applications
| Bech32 Encoded Tx Position References
| Велеслав, Jonas Schnelli, Daniel Pape
| Informational
| Draft
|- style="background-color: #cfffcf"
| [[bip-0137.mediawiki|137]]
| Applications
| Signatures of Messages using Private Keys
| Christopher Gilliard
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0140.mediawiki|140]]
| Consensus (soft fork)
| Normalized TXID
| Christian Decker
| Standard
| Rejected
|- style="background-color: #cfffcf"
| [[bip-0141.mediawiki|141]]
| Consensus (soft fork)
| Segregated Witness (Consensus layer)
| Eric Lombrozo, Johnson Lau, Pieter Wuille
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0142.mediawiki|142]]
| Applications
| Address Format for Segregated Witness
| Johnson Lau
| Standard
| Withdrawn
|- style="background-color: #cfffcf"
| [[bip-0143.mediawiki|143]]
| Consensus (soft fork)
| Transaction Signature Verification for Version 0 Witness Program
| Johnson Lau, Pieter Wuille
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0144.mediawiki|144]]
| Peer Services
| Segregated Witness (Peer Services)
| Eric Lombrozo, Pieter Wuille
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0145.mediawiki|145]]
| API/RPC
| getblocktemplate Updates for Segregated Witness
| Luke Dashjr
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0146.mediawiki|146]]
| Consensus (soft fork)
| Dealing with signature encoding malleability
| Johnson Lau, Pieter Wuille
| Standard
| Withdrawn
|- style="background-color: #cfffcf"
| [[bip-0147.mediawiki|147]]
| Consensus (soft fork)
| Dealing with dummy stack element malleability
| Johnson Lau
| Standard
| Final
|- style="background-color: #cfffcf"
| [[bip-0148.mediawiki|148]]
| Consensus (soft fork)
| Mandatory activation of segwit deployment
| Shaolin Fry
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0149.mediawiki|149]]
| Consensus (soft fork)
| Segregated Witness (second deployment)
| Shaolin Fry
| Standard
| Withdrawn
|-
| [[bip-0150.mediawiki|150]]
| Peer Services
| Peer Authentication
| Jonas Schnelli
| Standard
| Draft
|- style="background-color: #ffcfcf"
| [[bip-0151.mediawiki|151]]
| Peer Services
| Peer-to-Peer Communication Encryption
| Jonas Schnelli
| Standard
| Replaced
|- style="background-color: #cfffcf"
| [[bip-0152.mediawiki|152]]
| Peer Services
| Compact Block Relay
| Matt Corallo
| Standard
| Final
|- style="background-color: #ffcfcf"
| [[bip-0154.mediawiki|154]]
| Peer Services
| Rate Limiting via peer specified challenges
| Karl-Johan Alm
| Standard
| Withdrawn
|-
| [[bip-0155.mediawiki|155]]
| Peer Services
| addrv2 message
| Wladimir J. van der Laan
| Standard
| Draft
|- style="background-color: #ffcfcf"
| [[bip-0156.mediawiki|156]]
| Peer Services
| Dandelion - Privacy Enh### Hi there 👋

<!--
**ibrahimkhled/ibrahimkhled** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->i
k
