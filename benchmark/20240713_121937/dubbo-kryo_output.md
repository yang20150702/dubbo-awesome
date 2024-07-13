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
# Warmup Iteration   1: 1.636 ops/ms
Iteration   1: 7.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.558 ops/ms


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
Iteration   1: 13.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.885 ops/ms


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
# Warmup Iteration   1: 5.897 ops/ms
Iteration   1: 14.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.450 ops/ms


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
# Warmup Iteration   1: 5.534 ops/ms
Iteration   1: 8.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.184 ops/ms


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
# Warmup Iteration   1: 3.714 ±(99.9%) 0.064 ms/op
Iteration   1: 2.115 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.115 ms/op


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
# Warmup Iteration   1: 3.215 ±(99.9%) 0.053 ms/op
Iteration   1: 1.743 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.743 ms/op


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
# Warmup Iteration   1: 3.505 ±(99.9%) 0.054 ms/op
Iteration   1: 1.917 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.917 ms/op


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
# Warmup Iteration   1: 4.174 ±(99.9%) 0.070 ms/op
Iteration   1: 3.141 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.141 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.079 ms/op
Iteration   1: 2.046 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   1.874 ms/op
                 createUser·p0.90:   2.429 ms/op
                 createUser·p0.95:   2.658 ms/op
                 createUser·p0.99:   7.269 ms/op
                 createUser·p0.999:  13.664 ms/op
                 createUser·p0.9999: 14.175 ms/op
                 createUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15822
  mean =      2.046 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 14462 
    [ 2.500,  3.750) = 961 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      7.269 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     14.175 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.085 ms/op
Iteration   1: 1.805 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.668 ms/op
                 existUser·p0.50:   1.718 ms/op
                 existUser·p0.90:   2.075 ms/op
                 existUser·p0.95:   2.314 ms/op
                 existUser·p0.99:   3.006 ms/op
                 existUser·p0.999:  15.390 ms/op
                 existUser·p0.9999: 15.803 ms/op
                 existUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17698
  mean =      1.805 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 17117 
    [ 2.500,  3.750) = 437 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.075 ms/op
     p(95.0000) =      2.314 ms/op
     p(99.0000) =      3.006 ms/op
     p(99.9000) =     15.390 ms/op
     p(99.9900) =     15.803 ms/op
     p(99.9990) =     15.942 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


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
# Warmup Iteration   1: 3.252 ±(99.9%) 0.081 ms/op
Iteration   1: 2.166 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   2.032 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   3.896 ms/op
                 getUser·p0.999:  14.504 ms/op
                 getUser·p0.9999: 14.722 ms/op
                 getUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14772
  mean =      2.166 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 12397 
    [ 2.500,  3.750) = 2131 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      3.896 ms/op
     p(99.9000) =     14.504 ms/op
     p(99.9900) =     14.722 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 4.782 ±(99.9%) 0.304 ms/op
Iteration   1: 3.471 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.210 ms/op
                 listUser·p0.999:  6.526 ms/op
                 listUser·p0.9999: 7.692 ms/op
                 listUser·p1.00:   7.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9211
  mean =      3.471 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 87 
    [2.000, 2.500) = 789 
    [2.500, 3.000) = 1841 
    [3.000, 3.500) = 1879 
    [3.500, 4.000) = 2668 
    [4.000, 4.500) = 1348 
    [4.500, 5.000) = 266 
    [5.000, 5.500) = 44 
    [5.500, 6.000) = 119 
    [6.000, 6.500) = 151 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =      6.526 ms/op
     p(99.9900) =      7.692 ms/op
     p(99.9990) =      7.692 ms/op
     p(99.9999) =      7.692 ms/op
    p(100.0000) =      7.692 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.558          ops/ms
ClientSimple.existUser                       thrpt         13.885          ops/ms
ClientSimple.getUser                         thrpt         14.450          ops/ms
ClientSimple.listUser                        thrpt          8.184          ops/ms
ClientSimple.createUser                       avgt          2.115           ms/op
ClientSimple.existUser                        avgt          1.743           ms/op
ClientSimple.getUser                          avgt          1.917           ms/op
ClientSimple.listUser                         avgt          3.141           ms/op
ClientSimple.createUser                     sample  15822   2.046 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.677           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.874           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.429           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.269           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.664           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.175           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.270           ms/op
ClientSimple.existUser                      sample  17698   1.805 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.668           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.718           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.075           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.006           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.390           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.803           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.942           ms/op
ClientSimple.getUser                        sample  14772   2.166 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.627           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.032           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.896           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.504           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.722           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.746           ms/op
ClientSimple.listUser                       sample   9211   3.471 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.223           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.502           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.210           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.526           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.692           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.692           ms/op

Benchmark result is saved to 1720872911535.json
