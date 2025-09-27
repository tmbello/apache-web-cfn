Deploy a sample network configuration stack. For the Stack name use: SampleNetworkCrossStack
Deploy a new stack that will setup Apache on a Linux EC2 instnace and reference the sample network stack previously created.
Deploy template in us-west-2 region. Allocate an Elastic IP address using resources.
Reference all available variables from SampleNetworkCrossStack
Create a mapping function to dynamicall choosing regions.
Create parameters for requesting user inputs as much as possible.
Output the values of the private IPV4 address and DNS name of the EC2 instance
