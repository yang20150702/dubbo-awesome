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
# Warmup Iteration   1: 1.192 ops/ms
Iteration   1: 6.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.160 ops/ms


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
# Warmup Iteration   1: 5.519 ops/ms
Iteration   1: 11.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.780 ops/ms


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
# Warmup Iteration   1: 6.007 ops/ms
Iteration   1: 13.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.783 ops/ms


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
# Warmup Iteration   1: 6.178 ops/ms
Iteration   1: 8.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.447 ops/ms


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.070 ms/op
Iteration   1: 2.037 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.037 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.055 ms/op
Iteration   1: 1.775 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.775 ms/op


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
# Warmup Iteration   1: 3.115 ±(99.9%) 0.056 ms/op
Iteration   1: 1.828 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.828 ms/op


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
# Warmup Iteration   1: 4.236 ±(99.9%) 0.090 ms/op
Iteration   1: 3.436 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.436 ms/op


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
# Warmup Iteration   1: 3.863 ±(99.9%) 0.106 ms/op
Iteration   1: 2.113 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   1.944 ms/op
                 createUser·p0.90:   2.691 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 19.261 ms/op
                 createUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15343
  mean =      2.113 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 290 
    [ 1.250,  2.500) = 13088 
    [ 2.500,  3.750) = 1534 
    [ 3.750,  5.000) = 223 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     19.261 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 2.892 ±(99.9%) 0.077 ms/op
Iteration   1: 1.886 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.531 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  10.584 ms/op
                 existUser·p0.9999: 10.682 ms/op
                 existUser·p1.00:   10.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16958
  mean =      1.886 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 405 
    [ 1.250,  2.500) = 15661 
    [ 2.500,  3.750) = 732 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.531 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     10.682 ms/op
     p(99.9990) =     10.682 ms/op
     p(99.9999) =     10.682 ms/op
    p(100.0000) =     10.682 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.086 ms/op
Iteration   1: 2.036 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.470 ms/op
                 getUser·p0.50:   1.892 ms/op
                 getUser·p0.90:   2.490 ms/op
                 getUser·p0.95:   2.683 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  12.249 ms/op
                 getUser·p0.9999: 17.864 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15696
  mean =      2.036 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 14055 
    [ 2.500,  3.750) = 1318 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =     12.249 ms/op
     p(99.9900) =     17.864 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.123 ms/op
Iteration   1: 3.672 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.063 ms/op
                 listUser·p0.999:  20.578 ms/op
                 listUser·p0.9999: 21.365 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8882
  mean =      3.672 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 247 
    [ 2.500,  5.000) = 8347 
    [ 5.000,  7.500) = 228 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.063 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.160          ops/ms
ClientSimple.existUser                       thrpt         11.780          ops/ms
ClientSimple.getUser                         thrpt         13.783          ops/ms
ClientSimple.listUser                        thrpt          8.447          ops/ms
ClientSimple.createUser                       avgt          2.037           ms/op
ClientSimple.existUser                        avgt          1.775           ms/op
ClientSimple.getUser                          avgt          1.828           ms/op
ClientSimple.listUser                         avgt          3.436           ms/op
ClientSimple.createUser                     sample  15343   2.113 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.584           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.944           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.052           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.226           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.170           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.261           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.366           ms/op
ClientSimple.existUser                      sample  16958   1.886 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.600           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.654           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.584           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.682           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.682           ms/op
ClientSimple.getUser                        sample  15696   2.036 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.470           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.892           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.850           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.249           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.864           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.957           ms/op
ClientSimple.listUser                       sample   8882   3.672 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.227           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.576           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.063           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.578           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.365           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.365           ms/op

Benchmark result is saved to 1722687328411.json
