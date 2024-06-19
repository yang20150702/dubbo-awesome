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
# Warmup Iteration   1: 1.618 ops/ms
Iteration   1: 6.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.406 ops/ms


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
# Warmup Iteration   1: 5.963 ops/ms
Iteration   1: 12.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.776 ops/ms


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
# Warmup Iteration   1: 5.909 ops/ms
Iteration   1: 13.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.033 ops/ms


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
# Warmup Iteration   1: 5.656 ops/ms
Iteration   1: 8.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.952 ops/ms


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.073 ms/op
Iteration   1: 2.124 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.124 ms/op


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
# Warmup Iteration   1: 3.230 ±(99.9%) 0.058 ms/op
Iteration   1: 1.923 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.923 ms/op


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
# Warmup Iteration   1: 3.336 ±(99.9%) 0.065 ms/op
Iteration   1: 2.273 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.273 ms/op


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
# Warmup Iteration   1: 6.447 ±(99.9%) 0.145 ms/op
Iteration   1: 4.052 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.052 ms/op


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.114 ms/op
Iteration   1: 2.178 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.326 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   3.056 ms/op
                 createUser·p0.99:   9.929 ms/op
                 createUser·p0.999:  21.922 ms/op
                 createUser·p0.9999: 22.053 ms/op
                 createUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14677
  mean =      2.178 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13108 
    [ 2.500,  5.000) = 1294 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     21.922 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.078 ms/op
Iteration   1: 1.854 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   1.763 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.449 ms/op
                 existUser·p0.99:   3.056 ms/op
                 existUser·p0.999:  14.238 ms/op
                 existUser·p0.9999: 14.451 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17248
  mean =      1.854 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 437 
    [ 1.250,  2.500) = 16117 
    [ 2.500,  3.750) = 540 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.449 ms/op
     p(99.0000) =      3.056 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     14.451 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.135 ms/op
Iteration   1: 2.045 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.522 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.437 ms/op
                 getUser·p0.95:   2.605 ms/op
                 getUser·p0.99:   3.571 ms/op
                 getUser·p0.999:  13.572 ms/op
                 getUser·p0.9999: 13.697 ms/op
                 getUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15626
  mean =      2.045 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 286 
    [ 1.250,  2.500) = 14204 
    [ 2.500,  3.750) = 1004 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      3.571 ms/op
     p(99.9000) =     13.572 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     13.697 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


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
# Warmup Iteration   1: 4.632 ±(99.9%) 0.148 ms/op
Iteration   1: 3.336 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.293 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.134 ms/op
                 listUser·p0.999:  7.581 ms/op
                 listUser·p0.9999: 10.666 ms/op
                 listUser·p1.00:   10.666 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9607
  mean =      3.336 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 59 
    [ 2.000,  3.000) = 3590 
    [ 3.000,  4.000) = 4379 
    [ 4.000,  5.000) = 1367 
    [ 5.000,  6.000) = 110 
    [ 6.000,  7.000) = 38 
    [ 7.000,  8.000) = 63 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.134 ms/op
     p(99.9000) =      7.581 ms/op
     p(99.9900) =     10.666 ms/op
     p(99.9990) =     10.666 ms/op
     p(99.9999) =     10.666 ms/op
    p(100.0000) =     10.666 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.406          ops/ms
ClientSimple.existUser                       thrpt         12.776          ops/ms
ClientSimple.getUser                         thrpt         13.033          ops/ms
ClientSimple.listUser                        thrpt          8.952          ops/ms
ClientSimple.createUser                       avgt          2.124           ms/op
ClientSimple.existUser                        avgt          1.923           ms/op
ClientSimple.getUser                          avgt          2.273           ms/op
ClientSimple.listUser                         avgt          4.052           ms/op
ClientSimple.createUser                     sample  14677   2.178 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.326           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.056           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.929           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.922           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.053           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.053           ms/op
ClientSimple.existUser                      sample  17248   1.854 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.635           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.763           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.056           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.238           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.451           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.451           ms/op
ClientSimple.getUser                        sample  15626   2.045 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.522           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.437           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.571           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.572           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.697           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.697           ms/op
ClientSimple.listUser                       sample   9607   3.336 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.276           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.293           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.134           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.581           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.666           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.666           ms/op

Benchmark result is saved to 1718757680536.json
