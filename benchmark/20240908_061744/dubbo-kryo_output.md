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
# Warmup Iteration   1: 2.119 ops/ms
Iteration   1: 7.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.652 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.375 ops/ms
Iteration   1: 13.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.363 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.954 ops/ms
Iteration   1: 13.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.480 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.510 ops/ms
Iteration   1: 7.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.632 ops/ms


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.063 ms/op
Iteration   1: 2.262 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.262 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.204 ±(99.9%) 0.056 ms/op
Iteration   1: 1.704 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.704 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.054 ms/op
Iteration   1: 2.036 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.036 ms/op


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
# Warmup Iteration   1: 3.934 ±(99.9%) 0.070 ms/op
Iteration   1: 3.147 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.147 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.299 ±(99.9%) 0.079 ms/op
Iteration   1: 2.044 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   1.765 ms/op
                 createUser·p0.90:   2.695 ms/op
                 createUser·p0.95:   3.047 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  13.323 ms/op
                 createUser·p0.9999: 13.657 ms/op
                 createUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15600
  mean =      2.044 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 205 
    [ 1.250,  2.500) = 12772 
    [ 2.500,  3.750) = 2204 
    [ 3.750,  5.000) = 156 
    [ 5.000,  6.250) = 141 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.695 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     13.323 ms/op
     p(99.9900) =     13.657 ms/op
     p(99.9990) =     13.877 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.116 ±(99.9%) 0.061 ms/op
Iteration   1: 1.915 ±(99.9%) 0.047 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.204 ms/op
                 existUser·p0.95:   2.372 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  41.943 ms/op
                 existUser·p0.9999: 42.140 ms/op
                 existUser·p1.00:   42.140 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16801
  mean =      1.915 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16687 
    [ 5.000, 10.000) = 50 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.204 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      3.346 ms/op
     p(99.9000) =     41.943 ms/op
     p(99.9900) =     42.140 ms/op
     p(99.9990) =     42.140 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


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
# Warmup Iteration   1: 3.366 ±(99.9%) 0.085 ms/op
Iteration   1: 2.035 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.347 ms/op
                 getUser·p0.50:   1.958 ms/op
                 getUser·p0.90:   2.576 ms/op
                 getUser·p0.95:   2.785 ms/op
                 getUser·p0.99:   3.889 ms/op
                 getUser·p0.999:  15.204 ms/op
                 getUser·p0.9999: 15.401 ms/op
                 getUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15846
  mean =      2.035 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 289 
    [ 1.250,  2.500) = 13581 
    [ 2.500,  3.750) = 1786 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      3.889 ms/op
     p(99.9000) =     15.204 ms/op
     p(99.9900) =     15.401 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.125 ms/op
Iteration   1: 3.208 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.129 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.200 ms/op
                 listUser·p0.999:  10.898 ms/op
                 listUser·p0.9999: 11.140 ms/op
                 listUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10103
  mean =      3.208 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 144 
    [ 2.000,  3.000) = 4448 
    [ 3.000,  4.000) = 4361 
    [ 4.000,  5.000) = 849 
    [ 5.000,  6.000) = 195 
    [ 6.000,  7.000) = 40 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 25 
    [ 9.000, 10.000) = 7 
    [10.000, 11.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.200 ms/op
     p(99.9000) =     10.898 ms/op
     p(99.9900) =     11.140 ms/op
     p(99.9990) =     11.141 ms/op
     p(99.9999) =     11.141 ms/op
    p(100.0000) =     11.141 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.652          ops/ms
ClientSimple.existUser                       thrpt         13.363          ops/ms
ClientSimple.getUser                         thrpt         13.480          ops/ms
ClientSimple.listUser                        thrpt          7.632          ops/ms
ClientSimple.createUser                       avgt          2.262           ms/op
ClientSimple.existUser                        avgt          1.704           ms/op
ClientSimple.getUser                          avgt          2.036           ms/op
ClientSimple.listUser                         avgt          3.147           ms/op
ClientSimple.createUser                     sample  15600   2.044 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.593           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.765           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.695           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.988           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.323           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.657           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.877           ms/op
ClientSimple.existUser                      sample  16801   1.915 ± 0.047   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.663           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.796           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.204           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.346           ms/op
ClientSimple.existUser:existUser·p0.999     sample         41.943           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         42.140           ms/op
ClientSimple.existUser:existUser·p1.00      sample         42.140           ms/op
ClientSimple.getUser                        sample  15846   2.035 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.347           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.958           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.785           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.889           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.204           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.401           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.401           ms/op
ClientSimple.listUser                       sample  10103   3.208 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.151           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.129           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.055           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.200           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.898           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.140           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.141           ms/op

Benchmark result is saved to 1725775995722.json
