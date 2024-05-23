# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.698 ops/ms
Iteration   1: 7.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.010 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.972 ops/ms
Iteration   1: 13.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.024 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.246 ops/ms
Iteration   1: 12.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.962 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.480 ops/ms
Iteration   1: 8.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.152 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.068 ±(99.9%) 0.066 ms/op
Iteration   1: 2.215 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.215 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.114 ±(99.9%) 0.054 ms/op
Iteration   1: 1.715 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.715 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.182 ±(99.9%) 0.050 ms/op
Iteration   1: 1.954 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.954 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.423 ±(99.9%) 0.089 ms/op
Iteration   1: 3.102 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.102 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.468 ±(99.9%) 0.081 ms/op
Iteration   1: 1.975 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.305 ms/op
                 createUser·p0.50:   1.763 ms/op
                 createUser·p0.90:   2.757 ms/op
                 createUser·p0.95:   3.019 ms/op
                 createUser·p0.99:   4.028 ms/op
                 createUser·p0.999:  14.389 ms/op
                 createUser·p0.9999: 14.954 ms/op
                 createUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16184
  mean =      1.975 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 916 
    [ 1.250,  2.500) = 12488 
    [ 2.500,  3.750) = 2579 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.305 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      4.028 ms/op
     p(99.9000) =     14.389 ms/op
     p(99.9900) =     14.954 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.173 ±(99.9%) 0.108 ms/op
Iteration   1: 1.725 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   1.630 ms/op
                 existUser·p0.90:   2.249 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   2.871 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 11.971 ms/op
                 existUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18656
  mean =      1.725 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1801 
    [ 1.250,  2.500) = 16159 
    [ 2.500,  3.750) = 578 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.630 ms/op
     p(90.0000) =      2.249 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      2.871 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     11.971 ms/op
     p(99.9990) =     12.042 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.227 ±(99.9%) 0.077 ms/op
Iteration   1: 1.805 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   1.712 ms/op
                 getUser·p0.90:   2.126 ms/op
                 getUser·p0.95:   2.384 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  16.721 ms/op
                 getUser·p0.9999: 17.447 ms/op
                 getUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17722
  mean =      1.805 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 579 
    [ 1.250,  2.500) = 16482 
    [ 2.500,  3.750) = 492 
    [ 3.750,  5.000) = 41 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.126 ms/op
     p(95.0000) =      2.384 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =     16.721 ms/op
     p(99.9900) =     17.447 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.353 ±(99.9%) 0.117 ms/op
Iteration   1: 3.769 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.604 ms/op
                 listUser·p0.999:  14.672 ms/op
                 listUser·p0.9999: 14.795 ms/op
                 listUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8489
  mean =      3.769 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 506 
    [ 2.500,  3.750) = 3714 
    [ 3.750,  5.000) = 3915 
    [ 5.000,  6.250) = 168 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.604 ms/op
     p(99.9000) =     14.672 ms/op
     p(99.9900) =     14.795 ms/op
     p(99.9990) =     14.795 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.010          ops/ms
ClientSimple.existUser                       thrpt         13.024          ops/ms
ClientSimple.getUser                         thrpt         12.962          ops/ms
ClientSimple.listUser                        thrpt          8.152          ops/ms
ClientSimple.createUser                       avgt          2.215           ms/op
ClientSimple.existUser                        avgt          1.715           ms/op
ClientSimple.getUser                          avgt          1.954           ms/op
ClientSimple.listUser                         avgt          3.102           ms/op
ClientSimple.createUser                     sample  16184   1.975 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.305           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.763           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.028           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.389           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.954           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.106           ms/op
ClientSimple.existUser                      sample  18656   1.725 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.579           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.630           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.249           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.871           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.354           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.971           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.042           ms/op
ClientSimple.getUser                        sample  17722   1.805 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.530           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.712           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.126           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.686           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.721           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.447           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.498           ms/op
ClientSimple.listUser                       sample   8489   3.769 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.015           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.752           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.604           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.672           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.795           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.795           ms/op

Benchmark result is saved to 1716487902985.json
