Data Set Information:

This is an event log of an incident management process extracted from data gathered from the audit system of an instance of the ServiceNowTM platform used by an IT company. The event log is enriched with data loaded from a relational database underlying a corresponding process-aware information system. Information was anonymized for privacy.

Number of instances: 141,712 events (24,918 incidents)
Number of attributes: 36 attributes (1 case identifier, 1 state identifier, 32 descriptive attributes, 2 dependent variables)

Attribute Information:

number: incident identifier (24,918 different values);
incident state: eight levels controlling the incident management process transitions from opening until closing the case;
active: boolean attribute that shows whether the record is active or closed/canceled;
reassignment_count: number of times the incident has the group or the support analysts changed;
reopen_count: number of times the incident resolution was rejected by the caller;
sys_mod_count: number of incident updates until that moment;
made_sla: boolean attribute that shows whether the incident exceeded the target SLA;
caller_id: identifier of the user affected;
opened_by: identifier of the user who reported the incident;
opened_at: incident user opening date and time;
sys_created_by: identifier of the user who registered the incident;
sys_created_at: incident system creation date and time;
sys_updated_by: identifier of the user who updated the incident and generated the current log record;
sys_updated_at: incident system update date and time;
contact_type: categorical attribute that shows by what means the incident was reported;
location: identifier of the location of the place affected;
category: first-level description of the affected service;
subcategory: second-level description of the affected service (related to the first level description, i.e., to category);
u_symptom: description of the user perception about service availability;
cmdb_ci: (confirmation item) identifier used to report the affected item (not mandatory);
impact: description of the impact caused by the incident (values: 1â€“High; 2â€“Medium; 3â€“Low);
urgency: description of the urgency informed by the user for the incident resolution (values: 1â€“High; 2â€“Medium; 3â€“Low);
priority: calculated by the system based on 'impact' and 'urgency';
assignment_group: identifier of the support group in charge of the incident;
assigned_to: identifier of the user in charge of the incident;
knowledge: boolean attribute that shows whether a knowledge base document was used to resolve the incident;
u_priority_confirmation: boolean attribute that shows whether the priority field has been double-checked;
notify: categorical attribute that shows whether notifications were generated for the incident;
problem_id: identifier of the problem associated with the incident;
rfc: (request for change) identifier of the change request associated with the incident;
vendor: identifier of the vendor in charge of the incident;
caused_by: identifier of the RFC responsible by the incident;
close_code: identifier of the resolution of the incident;
resolved_by: identifier of the user who resolved the incident;
resolved_at: incident user resolution date and time (dependent variable);
closed_at: incident user close date and time (dependent variable).
