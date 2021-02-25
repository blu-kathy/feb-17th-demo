# feb-17th-demo

good commit

add another good commit first
bad commit
azure ad secret
`azuRE_ad_client_id="7075aa77-81ef-46eb-ae22-d768babeed21"`

add another commit
this commit should not trigger an event because
we already sent an event for this PR with that secret ^^
(de-duplication)


add another bad commit
this should trigger an event because
we found a new secret (should have updated summary)
`azuRE_ad_client_id="7175aa76-91ef-46eb-ae22-d768babeed31"`
