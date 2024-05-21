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
# Warmup Iteration   1: 0.827 ops/ms
Iteration   1: 5.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.216 ops/ms


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
# Warmup Iteration   1: 5.980 ops/ms
Iteration   1: 12.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.192 ops/ms


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
# Warmup Iteration   1: 5.735 ops/ms
Iteration   1: 13.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.511 ops/ms


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
# Warmup Iteration   1: 5.729 ops/ms
Iteration   1: 8.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.667 ops/ms


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.068 ms/op
Iteration   1: 2.203 ±(99.9%) 0.009 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.052 ms/op
Iteration   1: 2.147 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.147 ms/op


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
# Warmup Iteration   1: 3.088 ±(99.9%) 0.052 ms/op
Iteration   1: 2.010 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.010 ms/op


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.090 ms/op
Iteration   1: 3.672 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.672 ms/op


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
# Warmup Iteration   1: 3.462 ±(99.9%) 0.094 ms/op
Iteration   1: 2.013 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   1.872 ms/op
                 createUser·p0.90:   2.433 ms/op
                 createUser·p0.95:   2.761 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  15.011 ms/op
                 createUser·p0.9999: 16.821 ms/op
                 createUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15885
  mean =      2.013 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 277 
    [ 1.250,  2.500) = 14279 
    [ 2.500,  3.750) = 977 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     15.011 ms/op
     p(99.9900) =     16.821 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 3.201 ±(99.9%) 0.078 ms/op
Iteration   1: 1.748 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   1.649 ms/op
                 existUser·p0.90:   2.073 ms/op
                 existUser·p0.95:   2.286 ms/op
                 existUser·p0.99:   2.983 ms/op
                 existUser·p0.999:  13.418 ms/op
                 existUser·p0.9999: 13.784 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18469
  mean =      1.748 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 17904 
    [ 2.500,  3.750) = 312 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      1.649 ms/op
     p(90.0000) =      2.073 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      2.983 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     13.784 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.078 ms/op
Iteration   1: 2.056 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   1.905 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   3.341 ms/op
                 getUser·p0.999:  12.582 ms/op
                 getUser·p0.9999: 12.860 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15541
  mean =      2.056 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 13069 
    [ 2.500,  3.750) = 2305 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      3.341 ms/op
     p(99.9000) =     12.582 ms/op
     p(99.9900) =     12.860 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.161 ms/op
Iteration   1: 3.248 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.097 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.928 ms/op
                 listUser·p0.999:  8.020 ms/op
                 listUser·p0.9999: 9.077 ms/op
                 listUser·p1.00:   9.077 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9838
  mean =      3.248 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 17 
    [ 1.500,  2.000) = 84 
    [ 2.000,  2.500) = 538 
    [ 2.500,  3.000) = 3797 
    [ 3.000,  3.500) = 2426 
    [ 3.500,  4.000) = 1860 
    [ 4.000,  4.500) = 681 
    [ 4.500,  5.000) = 183 
    [ 5.000,  5.500) = 82 
    [ 5.500,  6.000) = 77 
    [ 6.000,  6.500) = 21 
    [ 6.500,  7.000) = 37 
    [ 7.000,  7.500) = 11 
    [ 7.500,  8.000) = 10 
    [ 8.000,  8.500) = 10 
    [ 8.500,  9.000) = 3 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.928 ms/op
     p(99.9000) =      8.020 ms/op
     p(99.9900) =      9.077 ms/op
     p(99.9990) =      9.077 ms/op
     p(99.9999) =      9.077 ms/op
    p(100.0000) =      9.077 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.216          ops/ms
ClientSimple.existUser                       thrpt         12.192          ops/ms
ClientSimple.getUser                         thrpt         13.511          ops/ms
ClientSimple.listUser                        thrpt          8.667          ops/ms
ClientSimple.createUser                       avgt          2.203           ms/op
ClientSimple.existUser                        avgt          2.147           ms/op
ClientSimple.getUser                          avgt          2.010           ms/op
ClientSimple.listUser                         avgt          3.672           ms/op
ClientSimple.createUser                     sample  15885   2.013 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.702           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.872           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.433           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.841           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.011           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.821           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.908           ms/op
ClientSimple.existUser                      sample  18469   1.748 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.639           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.649           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.073           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.983           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.418           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.784           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.812           ms/op
ClientSimple.getUser                        sample  15541   2.056 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.651           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.905           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.341           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.582           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.860           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.878           ms/op
ClientSimple.listUser                       sample   9838   3.248 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.247           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.097           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.928           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.020           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.077           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.077           ms/op

Benchmark result is saved to 1716271983621.json
