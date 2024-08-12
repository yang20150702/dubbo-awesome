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
# Warmup Iteration   1: 1.376 ops/ms
Iteration   1: 6.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.610 ops/ms


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
# Warmup Iteration   1: 6.523 ops/ms
Iteration   1: 13.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.801 ops/ms


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
# Warmup Iteration   1: 5.065 ops/ms
Iteration   1: 13.898 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.898 ops/ms


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
# Warmup Iteration   1: 5.035 ops/ms
Iteration   1: 8.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.974 ops/ms


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.068 ms/op
Iteration   1: 2.089 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.089 ms/op


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
# Warmup Iteration   1: 3.019 ±(99.9%) 0.051 ms/op
Iteration   1: 1.956 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.956 ms/op


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.071 ms/op
Iteration   1: 2.022 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.022 ms/op


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
# Warmup Iteration   1: 6.174 ±(99.9%) 0.149 ms/op
Iteration   1: 3.219 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.219 ms/op


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.124 ms/op
Iteration   1: 2.775 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.256 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   10.109 ms/op
                 createUser·p0.999:  12.607 ms/op
                 createUser·p0.9999: 19.787 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11551
  mean =      2.775 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 4654 
    [ 2.500,  3.750) = 6350 
    [ 3.750,  5.000) = 220 
    [ 5.000,  6.250) = 118 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.256 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     12.607 ms/op
     p(99.9900) =     19.787 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 2.858 ±(99.9%) 0.064 ms/op
Iteration   1: 1.517 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   1.411 ms/op
                 existUser·p0.90:   1.870 ms/op
                 existUser·p0.95:   2.130 ms/op
                 existUser·p0.99:   2.499 ms/op
                 existUser·p0.999:  14.565 ms/op
                 existUser·p0.9999: 15.003 ms/op
                 existUser·p1.00:   15.122 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 21045
  mean =      1.517 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3966 
    [ 1.250,  2.500) = 16871 
    [ 2.500,  3.750) = 140 
    [ 3.750,  5.000) = 4 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      1.411 ms/op
     p(90.0000) =      1.870 ms/op
     p(95.0000) =      2.130 ms/op
     p(99.0000) =      2.499 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     15.003 ms/op
     p(99.9990) =     15.122 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.082 ms/op
Iteration   1: 1.954 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   1.942 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.802 ms/op
                 getUser·p0.99:   4.126 ms/op
                 getUser·p0.999:  11.643 ms/op
                 getUser·p0.9999: 12.091 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16365
  mean =      1.954 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1103 
    [ 1.250,  2.500) = 13536 
    [ 2.500,  3.750) = 1536 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      4.126 ms/op
     p(99.9000) =     11.643 ms/op
     p(99.9900) =     12.091 ms/op
     p(99.9990) =     12.091 ms/op
     p(99.9999) =     12.091 ms/op
    p(100.0000) =     12.091 ms/op


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
# Warmup Iteration   1: 4.884 ±(99.9%) 0.163 ms/op
Iteration   1: 3.243 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   9.315 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9942
  mean =      3.243 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2157 
    [ 2.500,  5.000) = 7336 
    [ 5.000,  7.500) = 277 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      9.315 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     20.939 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.610          ops/ms
ClientSimple.existUser                       thrpt         13.801          ops/ms
ClientSimple.getUser                         thrpt         13.898          ops/ms
ClientSimple.listUser                        thrpt          8.974          ops/ms
ClientSimple.createUser                       avgt          2.089           ms/op
ClientSimple.existUser                        avgt          1.956           ms/op
ClientSimple.getUser                          avgt          2.022           ms/op
ClientSimple.listUser                         avgt          3.219           ms/op
ClientSimple.createUser                     sample  11551   2.775 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.069           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.256           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.703           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.109           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.607           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.787           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.792           ms/op
ClientSimple.existUser                      sample  21045   1.517 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.556           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.411           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.870           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.565           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.003           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.122           ms/op
ClientSimple.getUser                        sample  16365   1.954 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.692           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.942           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.802           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.126           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.643           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.091           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.091           ms/op
ClientSimple.listUser                       sample   9942   3.243 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.094           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.900           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.166           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.315           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.956           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.939           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.939           ms/op

Benchmark result is saved to 1723486447201.json
