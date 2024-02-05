# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.203 ops/ms
Iteration   1: 5.641 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.641 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.456 ops/ms
Iteration   1: 14.308 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.308 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.995 ops/ms
Iteration   1: 8.326 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.326 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.030 ops/ms
Iteration   1: 3.485 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.485 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.748 ±(99.9%) 0.082 ms/op
Iteration   1: 3.197 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.197 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.276 ±(99.9%) 0.036 ms/op
Iteration   1: 1.810 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.810 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.903 ±(99.9%) 0.064 ms/op
Iteration   1: 3.154 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.154 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.826 ±(99.9%) 0.220 ms/op
Iteration   1: 8.381 ±(99.9%) 0.090 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.381 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.445 ±(99.9%) 0.154 ms/op
Iteration   1: 3.268 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   7.455 ms/op
                 createUser·p0.999:  12.754 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9785
  mean =      3.268 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 933 
    [ 2.500,  3.750) = 7010 
    [ 3.750,  5.000) = 1582 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     12.754 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.131 ±(99.9%) 0.069 ms/op
Iteration   1: 1.731 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   1.690 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.384 ms/op
                 existUser·p0.99:   3.179 ms/op
                 existUser·p0.999:  3.816 ms/op
                 existUser·p0.9999: 6.884 ms/op
                 existUser·p1.00:   7.578 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18468
  mean =      1.731 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 71 
    [1.000, 1.500) = 5195 
    [1.500, 2.000) = 9582 
    [2.000, 2.500) = 2932 
    [2.500, 3.000) = 435 
    [3.000, 3.500) = 167 
    [3.500, 4.000) = 81 
    [4.000, 4.500) = 2 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 0 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.384 ms/op
     p(99.0000) =      3.179 ms/op
     p(99.9000) =      3.816 ms/op
     p(99.9900) =      6.884 ms/op
     p(99.9990) =      7.578 ms/op
     p(99.9999) =      7.578 ms/op
    p(100.0000) =      7.578 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 5.182 ±(99.9%) 0.138 ms/op
Iteration   1: 3.553 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   3.498 ms/op
                 getUser·p0.90:   4.262 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  13.025 ms/op
                 getUser·p0.9999: 16.237 ms/op
                 getUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9016
  mean =      3.553 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 475 
    [ 2.500,  3.750) = 5429 
    [ 3.750,  5.000) = 2917 
    [ 5.000,  6.250) = 115 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.262 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     16.237 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.158 ±(99.9%) 0.445 ms/op
Iteration   1: 8.453 ±(99.9%) 0.130 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   8.036 ms/op
                 listUser·p0.90:   10.697 ms/op
                 listUser·p0.95:   12.228 ms/op
                 listUser·p0.99:   19.146 ms/op
                 listUser·p0.999:  25.735 ms/op
                 listUser·p0.9999: 26.280 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3770
  mean =      8.453 ±(99.9%) 0.130 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 42 
    [ 5.000,  7.500) = 1354 
    [ 7.500, 10.000) = 1764 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      8.036 ms/op
     p(90.0000) =     10.697 ms/op
     p(95.0000) =     12.228 ms/op
     p(99.0000) =     19.146 ms/op
     p(99.9000) =     25.735 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.641          ops/ms
Client.existUser                       thrpt         14.308          ops/ms
Client.getUser                         thrpt          8.326          ops/ms
Client.listUser                        thrpt          3.485          ops/ms
Client.createUser                       avgt          3.197           ms/op
Client.existUser                        avgt          1.810           ms/op
Client.getUser                          avgt          3.154           ms/op
Client.listUser                         avgt          8.381           ms/op
Client.createUser                     sample   9785   3.268 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.335           ms/op
Client.createUser:createUser·p0.50    sample          3.072           ms/op
Client.createUser:createUser·p0.90    sample          4.133           ms/op
Client.createUser:createUser·p0.95    sample          4.571           ms/op
Client.createUser:createUser·p0.99    sample          7.455           ms/op
Client.createUser:createUser·p0.999   sample         12.754           ms/op
Client.createUser:createUser·p0.9999  sample         13.730           ms/op
Client.createUser:createUser·p1.00    sample         13.730           ms/op
Client.existUser                      sample  18468   1.731 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.724           ms/op
Client.existUser:existUser·p0.50      sample          1.690           ms/op
Client.existUser:existUser·p0.90      sample          2.191           ms/op
Client.existUser:existUser·p0.95      sample          2.384           ms/op
Client.existUser:existUser·p0.99      sample          3.179           ms/op
Client.existUser:existUser·p0.999     sample          3.816           ms/op
Client.existUser:existUser·p0.9999    sample          6.884           ms/op
Client.existUser:existUser·p1.00      sample          7.578           ms/op
Client.getUser                        sample   9016   3.553 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          1.122           ms/op
Client.getUser:getUser·p0.50          sample          3.498           ms/op
Client.getUser:getUser·p0.90          sample          4.262           ms/op
Client.getUser:getUser·p0.95          sample          4.596           ms/op
Client.getUser:getUser·p0.99          sample          5.726           ms/op
Client.getUser:getUser·p0.999         sample         13.025           ms/op
Client.getUser:getUser·p0.9999        sample         16.237           ms/op
Client.getUser:getUser·p1.00          sample         16.237           ms/op
Client.listUser                       sample   3770   8.453 ± 0.130   ms/op
Client.listUser:listUser·p0.00        sample          2.236           ms/op
Client.listUser:listUser·p0.50        sample          8.036           ms/op
Client.listUser:listUser·p0.90        sample         10.697           ms/op
Client.listUser:listUser·p0.95        sample         12.228           ms/op
Client.listUser:listUser·p0.99        sample         19.146           ms/op
Client.listUser:listUser·p0.999       sample         25.735           ms/op
Client.listUser:listUser·p0.9999      sample         26.280           ms/op
Client.listUser:listUser·p1.00        sample         26.280           ms/op
