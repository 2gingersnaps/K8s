# Schedule pods using labels and nodeSelectors

Label a node

Update deployment to make use of the new label

Taint one node with key1=value1:NoSchedule

Taint another node with key2=value2:NoSchedule

Create a new vanilla busybody deployment called “test” with rs set to 6

Try to schedule lots of pods across all nodes

Show that only one out of 3 nodes has any pods

Add a toleration to to the “test” deployment (this cancels out the taint)

vi test.yaml

Update deployment.spec.template.spec.tolerations
* key
* operator
* effect
