---
title: Workflow Assignment Changes
type: platform
---

#### Authorisation Assignment Expression

If this expression is left blank or evaluates to an empty string, documents can now be authorised directly by the current workflow user. 

Previously, documents with no authorisation assignment would require authorisation by the *manager* of the current workflow user. This can be replicated by setting **Authorisation Assignment Expression** to &apos;&lt;&lt;[DocumentWorkflowUserManagerEmail]&gt;&gt;&apos;

#### Assign document to form user's manager for approval

This workflow option has been removed. It can be replicated by setting **Assignment Expression** to &apos;&lt;&lt;[DocumentUserManagerEmail]&gt;&gt;&apos;