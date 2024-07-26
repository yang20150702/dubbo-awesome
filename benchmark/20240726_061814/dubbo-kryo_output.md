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
# Warmup Iteration   1: 1.347 ops/ms
Iteration   1: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.726 ops/ms


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
# Warmup Iteration   1: 6.166 ops/ms
Iteration   1: 13.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.958 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.921 ops/ms
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
# Warmup Iteration   1: 4.427 ops/ms
Iteration   1: 7.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.407 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.064 ms/op
Iteration   1: 2.153 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.153 ms/op


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.088 ms/op
Iteration   1: 1.790 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.790 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 2.993 ±(99.9%) 0.046 ms/op
Iteration   1: 2.177 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.177 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.431 ±(99.9%) 0.094 ms/op
Iteration   1: 3.662 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.662 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.139 ms/op
Iteration   1: 2.203 ±(99.9%) 0.080 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   2.028 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.802 ms/op
                 createUser·p0.99:   11.107 ms/op
                 createUser·p0.999:  58.065 ms/op
                 createUser·p0.9999: 58.465 ms/op
                 createUser·p1.00:   58.524 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14508
  mean =      2.203 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14313 
    [ 5.000, 10.000) = 3 
    [10.000, 15.000) = 127 
    [15.000, 20.000) = 33 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =     11.107 ms/op
     p(99.9000) =     58.065 ms/op
     p(99.9900) =     58.465 ms/op
     p(99.9990) =     58.524 ms/op
     p(99.9999) =     58.524 ms/op
    p(100.0000) =     58.524 ms/op


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
# Warmup Iteration   1: 3.078 ±(99.9%) 0.073 ms/op
Iteration   1: 1.942 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.471 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   4.197 ms/op
                 existUser·p0.999:  16.622 ms/op
                 existUser·p0.9999: 19.139 ms/op
                 existUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16471
  mean =      1.942 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15747 
    [ 2.500,  5.000) = 590 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      4.197 ms/op
     p(99.9000) =     16.622 ms/op
     p(99.9900) =     19.139 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.090 ms/op
Iteration   1: 1.986 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.410 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.458 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   3.948 ms/op
                 getUser·p0.999:  12.401 ms/op
                 getUser·p0.9999: 13.303 ms/op
                 getUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16104
  mean =      1.986 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 14486 
    [ 2.500,  3.750) = 1274 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.948 ms/op
     p(99.9000) =     12.401 ms/op
     p(99.9900) =     13.303 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.116 ms/op
Iteration   1: 3.419 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.367 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.614 ms/op
                 listUser·p0.999:  29.360 ms/op
                 listUser·p0.9999: 29.524 ms/op
                 listUser·p1.00:   29.524 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9435
  mean =      3.419 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1100 
    [ 2.500,  5.000) = 8192 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.614 ms/op
     p(99.9000) =     29.360 ms/op
     p(99.9900) =     29.524 ms/op
     p(99.9990) =     29.524 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.726          ops/ms
ClientSimple.existUser                       thrpt         13.958          ops/ms
ClientSimple.getUser                         thrpt         12.404          ops/ms
ClientSimple.listUser                        thrpt          7.407          ops/ms
ClientSimple.createUser                       avgt          2.153           ms/op
ClientSimple.existUser                        avgt          1.790           ms/op
ClientSimple.getUser                          avgt          2.177           ms/op
ClientSimple.listUser                         avgt          3.662           ms/op
ClientSimple.createUser                     sample  14508   2.203 ± 0.080   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.575           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.028           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.107           ms/op
ClientSimple.createUser:createUser·p0.999   sample         58.065           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         58.465           ms/op
ClientSimple.createUser:createUser·p1.00    sample         58.524           ms/op
ClientSimple.existUser                      sample  16471   1.942 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.471           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.806           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.197           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.622           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.139           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.233           ms/op
ClientSimple.getUser                        sample  16104   1.986 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.410           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.458           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.948           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.401           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.303           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.894           ms/op
ClientSimple.listUser                       sample   9435   3.419 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.212           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.367           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.129           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.614           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.360           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.524           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.524           ms/op

Benchmark result is saved to 1721974454087.json
