# Create a Kinesis Data Stream

---


In this section, you will create a new Kinesis Data Stream , this data stream handles incoming real-time flight schedule updates.

1. Using the AWS Console, navigate to the Amazon Kinesis services and press Get Started when prompted.

2. Select **Create data stream** to navigate to the Amazon Kinesis Data Stream service.
![Alt](/assets/images/streamprocess/sp1.png "Get Started")

3. When prompted, enter *input-stream* as your Kinesis Data Stream name.
Keep 'On demand' selected as your capacity mode, and leave all else as default.
![Alt](/assets/images/streamprocess/sp2.png "Get Started")
```
We will use on-demand for this workshop for simplicity. As discussed in the previous section, on-demand mode takes away the guesswork of shard estimation, and provisions capacity based on your throughput. Use provisioned mode if you have a predictable throughput for cost optimization.
```
Check out when to use [on-demand vs provisioned][1]
[1]:https://docs.aws.amazon.com/streams/latest/dev/how-do-i-size-a-stream.html

4. When finally created, you should see a status of Active on the stream.
![Alt](/assets/images/streamprocess/sp3.png "Get Started")
