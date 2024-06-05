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
# Warmup Iteration   1: 1.497 ops/ms
Iteration   1: 6.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.691 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.073 ops/ms
Iteration   1: 10.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.367 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.570 ops/ms
Iteration   1: 12.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.484 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.014 ops/ms
Iteration   1: 8.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.337 ops/ms


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.076 ms/op
Iteration   1: 2.378 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.378 ms/op


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
# Warmup Iteration   1: 3.555 ±(99.9%) 0.052 ms/op
Iteration   1: 2.190 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.190 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.057 ms/op
Iteration   1: 1.742 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.742 ms/op


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.071 ms/op
Iteration   1: 3.000 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.000 ms/op


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
# Warmup Iteration   1: 5.243 ±(99.9%) 0.384 ms/op
Iteration   1: 2.559 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.372 ms/op
                 createUser·p0.90:   3.183 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   12.009 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 20.128 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12499
  mean =      2.559 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7258 
    [ 2.500,  5.000) = 4911 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.372 ms/op
     p(90.0000) =      3.183 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =     12.009 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     20.128 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.126 ms/op
Iteration   1: 1.801 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.358 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   3.311 ms/op
                 existUser·p0.999:  11.125 ms/op
                 existUser·p0.9999: 12.093 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17760
  mean =      1.801 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 491 
    [ 1.250,  2.500) = 16556 
    [ 2.500,  3.750) = 596 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      3.311 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     12.093 ms/op
     p(99.9990) =     12.157 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


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
# Warmup Iteration   1: 3.142 ±(99.9%) 0.074 ms/op
Iteration   1: 2.011 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.454 ms/op
                 getUser·p0.50:   1.966 ms/op
                 getUser·p0.90:   2.548 ms/op
                 getUser·p0.95:   2.724 ms/op
                 getUser·p0.99:   4.012 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16044
  mean =      2.011 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14050 
    [ 2.500,  5.000) = 1921 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      4.012 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 4.584 ±(99.9%) 0.133 ms/op
Iteration   1: 3.573 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.332 ms/op
                 listUser·p0.999:  18.253 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8952
  mean =      3.573 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 927 
    [ 2.500,  3.750) = 4580 
    [ 3.750,  5.000) = 3013 
    [ 5.000,  6.250) = 337 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     18.253 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.691          ops/ms
ClientSimple.existUser                       thrpt         10.367          ops/ms
ClientSimple.getUser                         thrpt         12.484          ops/ms
ClientSimple.listUser                        thrpt          8.337          ops/ms
ClientSimple.createUser                       avgt          2.378           ms/op
ClientSimple.existUser                        avgt          2.190           ms/op
ClientSimple.getUser                          avgt          1.742           ms/op
ClientSimple.listUser                         avgt          3.000           ms/op
ClientSimple.createUser                     sample  12499   2.559 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.677           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.372           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.183           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.555           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.009           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.743           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.128           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.218           ms/op
ClientSimple.existUser                      sample  17760   1.801 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.358           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.311           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.125           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.093           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.157           ms/op
ClientSimple.getUser                        sample  16044   2.011 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.454           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.966           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.548           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.012           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.266           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.398           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.398           ms/op
ClientSimple.listUser                       sample   8952   3.573 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.130           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.518           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.332           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.253           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.104           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.104           ms/op

Benchmark result is saved to 1717589805362.json
