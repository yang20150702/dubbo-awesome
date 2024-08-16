# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.902 ops/ms
Iteration   1: 7.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.528 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.736 ops/ms
Iteration   1: 13.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.341 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.989 ops/ms
Iteration   1: 12.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.404 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.460 ops/ms
Iteration   1: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.496 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.463 ±(99.9%) 0.079 ms/op
Iteration   1: 2.051 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.051 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.710 ±(99.9%) 0.070 ms/op
Iteration   1: 2.078 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.078 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.348 ±(99.9%) 0.061 ms/op
Iteration   1: 2.093 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ±(99.9%) 0.097 ms/op
Iteration   1: 3.573 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.573 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.645 ±(99.9%) 0.099 ms/op
Iteration   1: 2.372 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   2.191 ms/op
                 createUser·p0.90:   2.785 ms/op
                 createUser·p0.95:   2.937 ms/op
                 createUser·p0.99:   8.505 ms/op
                 createUser·p0.999:  26.645 ms/op
                 createUser·p0.9999: 30.676 ms/op
                 createUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13688
  mean =      2.372 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10392 
    [ 2.500,  5.000) = 3011 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.785 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      8.505 ms/op
     p(99.9000) =     26.645 ms/op
     p(99.9900) =     30.676 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.913 ±(99.9%) 0.067 ms/op
Iteration   1: 1.766 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   1.675 ms/op
                 existUser·p0.90:   2.097 ms/op
                 existUser·p0.95:   2.220 ms/op
                 existUser·p0.99:   3.064 ms/op
                 existUser·p0.999:  21.522 ms/op
                 existUser·p0.9999: 22.065 ms/op
                 existUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18192
  mean =      1.766 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17907 
    [ 2.500,  5.000) = 221 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 7 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.097 ms/op
     p(95.0000) =      2.220 ms/op
     p(99.0000) =      3.064 ms/op
     p(99.9000) =     21.522 ms/op
     p(99.9900) =     22.065 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.279 ±(99.9%) 0.092 ms/op
Iteration   1: 2.350 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   2.257 ms/op
                 getUser·p0.90:   2.901 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  10.709 ms/op
                 getUser·p0.9999: 13.573 ms/op
                 getUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13596
  mean =      2.350 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 9499 
    [ 2.500,  3.750) = 3890 
    [ 3.750,  5.000) = 107 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.257 ms/op
     p(90.0000) =      2.901 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =     10.709 ms/op
     p(99.9900) =     13.573 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.812 ±(99.9%) 0.143 ms/op
Iteration   1: 3.554 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   3.453 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.763 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  19.728 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8990
  mean =      3.554 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 720 
    [ 2.500,  5.000) = 7912 
    [ 5.000,  7.500) = 293 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.763 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     19.728 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.528          ops/ms
ClientSimple.existUser                       thrpt         13.341          ops/ms
ClientSimple.getUser                         thrpt         12.404          ops/ms
ClientSimple.listUser                        thrpt          8.496          ops/ms
ClientSimple.createUser                       avgt          2.051           ms/op
ClientSimple.existUser                        avgt          2.078           ms/op
ClientSimple.getUser                          avgt          2.093           ms/op
ClientSimple.listUser                         avgt          3.573           ms/op
ClientSimple.createUser                     sample  13688   2.372 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.424           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.191           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.785           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.505           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.645           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.676           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.736           ms/op
ClientSimple.existUser                      sample  18192   1.766 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.500           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.675           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.097           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.064           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.522           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.065           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.118           ms/op
ClientSimple.getUser                        sample  13596   2.350 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.648           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.257           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.901           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.912           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.709           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.573           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.369           ms/op
ClientSimple.listUser                       sample   8990   3.554 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.738           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.453           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.763           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.906           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.728           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.808           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.808           ms/op

Benchmark result is saved to 1723831984918.json
