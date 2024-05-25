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
# Warmup Iteration   1: 1.760 ops/ms
Iteration   1: 7.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.079 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.420 ops/ms
Iteration   1: 12.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.347 ops/ms


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
# Warmup Iteration   1: 5.137 ops/ms
Iteration   1: 12.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.464 ops/ms


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
# Warmup Iteration   1: 4.588 ops/ms
Iteration   1: 8.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.644 ops/ms


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.087 ms/op
Iteration   1: 2.203 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.203 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.068 ms/op
Iteration   1: 1.860 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.063 ms/op
Iteration   1: 1.989 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.989 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.080 ms/op
Iteration   1: 3.730 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.730 ms/op


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.247 ms/op
Iteration   1: 2.231 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   2.005 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.855 ms/op
                 createUser·p0.99:   11.104 ms/op
                 createUser·p0.999:  30.966 ms/op
                 createUser·p0.9999: 31.064 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14323
  mean =      2.231 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12790 
    [ 2.500,  5.000) = 1332 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =     11.104 ms/op
     p(99.9000) =     30.966 ms/op
     p(99.9900) =     31.064 ms/op
     p(99.9990) =     31.064 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 2.937 ±(99.9%) 0.067 ms/op
Iteration   1: 2.113 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.015 ms/op
                 existUser·p0.90:   2.587 ms/op
                 existUser·p0.95:   2.712 ms/op
                 existUser·p0.99:   3.448 ms/op
                 existUser·p0.999:  13.967 ms/op
                 existUser·p0.9999: 14.368 ms/op
                 existUser·p1.00:   14.385 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15164
  mean =      2.113 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 375 
    [ 1.250,  2.500) = 12545 
    [ 2.500,  3.750) = 2105 
    [ 3.750,  5.000) = 5 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.015 ms/op
     p(90.0000) =      2.587 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      3.448 ms/op
     p(99.9000) =     13.967 ms/op
     p(99.9900) =     14.368 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


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
# Warmup Iteration   1: 3.414 ±(99.9%) 0.081 ms/op
Iteration   1: 2.209 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   2.095 ms/op
                 getUser·p0.90:   2.648 ms/op
                 getUser·p0.95:   2.863 ms/op
                 getUser·p0.99:   4.657 ms/op
                 getUser·p0.999:  20.137 ms/op
                 getUser·p0.9999: 20.698 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14474
  mean =      2.209 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12219 
    [ 2.500,  5.000) = 2154 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.095 ms/op
     p(90.0000) =      2.648 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      4.657 ms/op
     p(99.9000) =     20.137 ms/op
     p(99.9900) =     20.698 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 5.782 ±(99.9%) 0.152 ms/op
Iteration   1: 3.491 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.682 ms/op
                 listUser·p0.50:   3.400 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.623 ms/op
                 listUser·p0.9999: 15.778 ms/op
                 listUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9155
  mean =      3.491 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 567 
    [ 2.500,  3.750) = 5737 
    [ 3.750,  5.000) = 2513 
    [ 5.000,  6.250) = 178 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.623 ms/op
     p(99.9900) =     15.778 ms/op
     p(99.9990) =     15.778 ms/op
     p(99.9999) =     15.778 ms/op
    p(100.0000) =     15.778 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.079          ops/ms
ClientSimple.existUser                       thrpt         12.347          ops/ms
ClientSimple.getUser                         thrpt         12.464          ops/ms
ClientSimple.listUser                        thrpt          8.644          ops/ms
ClientSimple.createUser                       avgt          2.203           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          1.989           ms/op
ClientSimple.listUser                         avgt          3.730           ms/op
ClientSimple.createUser                     sample  14323   2.231 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.574           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.005           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.104           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.966           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.064           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.064           ms/op
ClientSimple.existUser                      sample  15164   2.113 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.536           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.015           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.587           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.712           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.448           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.967           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.368           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.385           ms/op
ClientSimple.getUser                        sample  14474   2.209 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.622           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.095           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.648           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.657           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.137           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.698           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.742           ms/op
ClientSimple.listUser                       sample   9155   3.491 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.682           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.400           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.988           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.623           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.778           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.778           ms/op

Benchmark result is saved to 1716660653942.json
