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
# Warmup Iteration   1: 2.017 ops/ms
Iteration   1: 5.104 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.104 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.275 ops/ms
Iteration   1: 10.938 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.938 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.648 ops/ms
Iteration   1: 8.142 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.142 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.933 ops/ms
Iteration   1: 3.738 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.738 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.650 ±(99.9%) 0.081 ms/op
Iteration   1: 3.133 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.133 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.056 ms/op
Iteration   1: 2.181 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.181 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.475 ±(99.9%) 0.096 ms/op
Iteration   1: 3.219 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.219 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 13.043 ±(99.9%) 0.182 ms/op
Iteration   1: 9.354 ±(99.9%) 0.109 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.354 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.313 ±(99.9%) 0.129 ms/op
Iteration   1: 3.228 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   9.606 ms/op
                 createUser·p0.999:  12.599 ms/op
                 createUser·p0.9999: 12.665 ms/op
                 createUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9989
  mean =      3.228 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1508 
    [ 2.500,  3.750) = 7232 
    [ 3.750,  5.000) = 921 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      9.606 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     12.665 ms/op
     p(99.9999) =     12.665 ms/op
    p(100.0000) =     12.665 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.131 ±(99.9%) 0.065 ms/op
Iteration   1: 2.019 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.469 ms/op
                 existUser·p0.50:   1.846 ms/op
                 existUser·p0.90:   2.757 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   4.710 ms/op
                 existUser·p0.999:  15.991 ms/op
                 existUser·p0.9999: 16.672 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15846
  mean =      2.019 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 647 
    [ 1.250,  2.500) = 13049 
    [ 2.500,  3.750) = 1841 
    [ 3.750,  5.000) = 172 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      1.846 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =     15.991 ms/op
     p(99.9900) =     16.672 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.890 ±(99.9%) 0.118 ms/op
Iteration   1: 2.902 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   2.785 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.987 ms/op
                 getUser·p0.99:   5.398 ms/op
                 getUser·p0.999:  17.760 ms/op
                 getUser·p0.9999: 18.212 ms/op
                 getUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11009
  mean =      2.902 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3817 
    [ 2.500,  3.750) = 6346 
    [ 3.750,  5.000) = 681 
    [ 5.000,  6.250) = 100 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.987 ms/op
     p(99.0000) =      5.398 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     18.212 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.065 ±(99.9%) 0.465 ms/op
Iteration   1: 8.380 ±(99.9%) 0.103 ms/op
                 listUser·p0.00:   3.142 ms/op
                 listUser·p0.50:   8.192 ms/op
                 listUser·p0.90:   10.733 ms/op
                 listUser·p0.95:   11.978 ms/op
                 listUser·p0.99:   14.238 ms/op
                 listUser·p0.999:  18.977 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3818
  mean =      8.380 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 51 
    [ 5.000,  7.500) = 1261 
    [ 7.500, 10.000) = 1881 
    [10.000, 12.500) = 487 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.142 ms/op
     p(50.0000) =      8.192 ms/op
     p(90.0000) =     10.733 ms/op
     p(95.0000) =     11.978 ms/op
     p(99.0000) =     14.238 ms/op
     p(99.9000) =     18.977 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.104          ops/ms
Client.existUser                       thrpt         10.938          ops/ms
Client.getUser                         thrpt          8.142          ops/ms
Client.listUser                        thrpt          3.738          ops/ms
Client.createUser                       avgt          3.133           ms/op
Client.existUser                        avgt          2.181           ms/op
Client.getUser                          avgt          3.219           ms/op
Client.listUser                         avgt          9.354           ms/op
Client.createUser                     sample   9989   3.228 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          1.031           ms/op
Client.createUser:createUser·p0.50    sample          3.064           ms/op
Client.createUser:createUser·p0.90    sample          3.891           ms/op
Client.createUser:createUser·p0.95    sample          4.448           ms/op
Client.createUser:createUser·p0.99    sample          9.606           ms/op
Client.createUser:createUser·p0.999   sample         12.599           ms/op
Client.createUser:createUser·p0.9999  sample         12.665           ms/op
Client.createUser:createUser·p1.00    sample         12.665           ms/op
Client.existUser                      sample  15846   2.019 ± 0.028   ms/op
Client.existUser:existUser·p0.00      sample          0.469           ms/op
Client.existUser:existUser·p0.50      sample          1.846           ms/op
Client.existUser:existUser·p0.90      sample          2.757           ms/op
Client.existUser:existUser·p0.95      sample          3.121           ms/op
Client.existUser:existUser·p0.99      sample          4.710           ms/op
Client.existUser:existUser·p0.999     sample         15.991           ms/op
Client.existUser:existUser·p0.9999    sample         16.672           ms/op
Client.existUser:existUser·p1.00      sample         16.777           ms/op
Client.getUser                        sample  11009   2.902 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          1.343           ms/op
Client.getUser:getUser·p0.50          sample          2.785           ms/op
Client.getUser:getUser·p0.90          sample          3.621           ms/op
Client.getUser:getUser·p0.95          sample          3.987           ms/op
Client.getUser:getUser·p0.99          sample          5.398           ms/op
Client.getUser:getUser·p0.999         sample         17.760           ms/op
Client.getUser:getUser·p0.9999        sample         18.212           ms/op
Client.getUser:getUser·p1.00          sample         18.219           ms/op
Client.listUser                       sample   3818   8.380 ± 0.103   ms/op
Client.listUser:listUser·p0.00        sample          3.142           ms/op
Client.listUser:listUser·p0.50        sample          8.192           ms/op
Client.listUser:listUser·p0.90        sample         10.733           ms/op
Client.listUser:listUser·p0.95        sample         11.978           ms/op
Client.listUser:listUser·p0.99        sample         14.238           ms/op
Client.listUser:listUser·p0.999       sample         18.977           ms/op
Client.listUser:listUser·p0.9999      sample         21.758           ms/op
Client.listUser:listUser·p1.00        sample         21.758           ms/op
