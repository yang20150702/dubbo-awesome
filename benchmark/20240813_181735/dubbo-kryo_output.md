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
# Warmup Iteration   1: 1.475 ops/ms
Iteration   1: 6.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.593 ops/ms


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
# Warmup Iteration   1: 5.957 ops/ms
Iteration   1: 11.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.803 ops/ms


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
# Warmup Iteration   1: 5.740 ops/ms
Iteration   1: 12.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.905 ops/ms


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
# Warmup Iteration   1: 4.950 ops/ms
Iteration   1: 8.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.899 ops/ms


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.109 ms/op
Iteration   1: 2.368 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.368 ms/op


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
# Warmup Iteration   1: 3.500 ±(99.9%) 0.076 ms/op
Iteration   1: 2.131 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.131 ms/op


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
# Warmup Iteration   1: 3.357 ±(99.9%) 0.055 ms/op
Iteration   1: 2.082 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.082 ms/op


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
# Warmup Iteration   1: 4.408 ±(99.9%) 0.086 ms/op
Iteration   1: 3.146 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.146 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.078 ms/op
Iteration   1: 1.933 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   1.798 ms/op
                 createUser·p0.90:   2.273 ms/op
                 createUser·p0.95:   2.417 ms/op
                 createUser·p0.99:   4.751 ms/op
                 createUser·p0.999:  18.809 ms/op
                 createUser·p0.9999: 22.457 ms/op
                 createUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16645
  mean =      1.933 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15995 
    [ 2.500,  5.000) = 522 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     22.457 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 2.992 ±(99.9%) 0.066 ms/op
Iteration   1: 1.833 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.416 ms/op
                 existUser·p0.50:   1.733 ms/op
                 existUser·p0.90:   2.363 ms/op
                 existUser·p0.95:   2.544 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  11.598 ms/op
                 existUser·p0.9999: 11.928 ms/op
                 existUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17551
  mean =      1.833 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1313 
    [ 1.250,  2.500) = 15195 
    [ 2.500,  3.750) = 849 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 45 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      1.733 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =     11.598 ms/op
     p(99.9900) =     11.928 ms/op
     p(99.9990) =     11.928 ms/op
     p(99.9999) =     11.928 ms/op
    p(100.0000) =     11.928 ms/op


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
# Warmup Iteration   1: 3.152 ±(99.9%) 0.075 ms/op
Iteration   1: 2.060 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.634 ms/op
                 getUser·p0.95:   2.810 ms/op
                 getUser·p0.99:   5.211 ms/op
                 getUser·p0.999:  15.122 ms/op
                 getUser·p0.9999: 15.591 ms/op
                 getUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15591
  mean =      2.060 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 274 
    [ 1.250,  2.500) = 12872 
    [ 2.500,  3.750) = 2253 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 80 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.634 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      5.211 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     15.591 ms/op
     p(99.9990) =     16.040 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.139 ms/op
Iteration   1: 3.360 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   0.736 ms/op
                 listUser·p0.50:   3.293 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  32.448 ms/op
                 listUser·p0.9999: 33.260 ms/op
                 listUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9343
  mean =      3.360 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2091 
    [ 2.500,  5.000) = 7021 
    [ 5.000,  7.500) = 144 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     32.448 ms/op
     p(99.9900) =     33.260 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.593          ops/ms
ClientSimple.existUser                       thrpt         11.803          ops/ms
ClientSimple.getUser                         thrpt         12.905          ops/ms
ClientSimple.listUser                        thrpt          8.899          ops/ms
ClientSimple.createUser                       avgt          2.368           ms/op
ClientSimple.existUser                        avgt          2.131           ms/op
ClientSimple.getUser                          avgt          2.082           ms/op
ClientSimple.listUser                         avgt          3.146           ms/op
ClientSimple.createUser                     sample  16645   1.933 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.523           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.798           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.273           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.751           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.809           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.457           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.479           ms/op
ClientSimple.existUser                      sample  17551   1.833 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.416           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.733           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.363           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.544           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.100           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.598           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.928           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.928           ms/op
ClientSimple.getUser                        sample  15591   2.060 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.752           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.211           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.122           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.591           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.040           ms/op
ClientSimple.listUser                       sample   9343   3.360 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.736           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.293           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.141           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.152           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.448           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         33.260           ms/op
ClientSimple.listUser:listUser·p1.00        sample         33.260           ms/op

Benchmark result is saved to 1723572811429.json
