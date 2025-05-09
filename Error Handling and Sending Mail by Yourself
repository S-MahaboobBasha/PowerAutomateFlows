actions(<action_name>)?['status'], 'Succeeded'
actions(<action_name>)?['status'], 'Failed'
actions(<action_name>)?['status'], 'Skipped'
actions(<action_name>)?['status'], 'TimedOut'

# condition
and ( equals(actions(<action_name>)?['status'], 'Succeeded'),
      equals(actions(<action_name>)?['status'], 'Failed'),
      equals(actions(<action_name>)?['status'], 'Skipped'),
      equals(actions(<action_name>)?['status'], 'TimedOut') 
    )

# Send an Email by yourself with something wrong with flow failed to fix

Hi Team,
Flow Failed!

# Expression : 

# workflow()['tags']['environmentName']
# workflow()['name']
# workflow()['run']['name']

# Flow Name : Provide Direct flow name it's not dynamic
# Flow Link :  https://make.powerautomate.com/environment/workflow()['tags']['environmentName']/flows/workflow()['name']/runs/workflow()['run']['name']
# Flow run history: https://make.powerautomate.com/environment/workflow()['tags']['environmentName']/flows/workflow()['name']/details

