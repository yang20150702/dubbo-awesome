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
# Warmup Iteration   1: 1.656 ops/ms
Iteration   1: 7.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.070 ops/ms


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
# Warmup Iteration   1: 5.516 ops/ms
Iteration   1: 12.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.431 ops/ms


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
# Warmup Iteration   1: 6.337 ops/ms
Iteration   1: 13.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.425 ops/ms


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
# Warmup Iteration   1: 4.241 ops/ms
Iteration   1: 8.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.335 ops/ms


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
# Warmup Iteration   1: 3.667 ±(99.9%) 0.072 ms/op
Iteration   1: 2.369 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.369 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.056 ms/op
Iteration   1: 1.869 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.869 ms/op


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
# Warmup Iteration   1: 4.128 ±(99.9%) 0.092 ms/op
Iteration   1: 1.772 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.772 ms/op


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.103 ms/op
Iteration   1: 3.159 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.159 ms/op


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
# Warmup Iteration   1: 3.712 ±(99.9%) 0.093 ms/op
Iteration   1: 2.294 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   2.050 ms/op
                 createUser·p0.90:   2.785 ms/op
                 createUser·p0.95:   3.185 ms/op
                 createUser·p0.99:   10.306 ms/op
                 createUser·p0.999:  15.696 ms/op
                 createUser·p0.9999: 18.206 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13968
  mean =      2.294 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 383 
    [ 1.250,  2.500) = 10749 
    [ 2.500,  3.750) = 2360 
    [ 3.750,  5.000) = 145 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      2.050 ms/op
     p(90.0000) =      2.785 ms/op
     p(95.0000) =      3.185 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     18.206 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.052 ±(99.9%) 0.076 ms/op
Iteration   1: 1.936 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   1.712 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.732 ms/op
                 existUser·p0.99:   3.449 ms/op
                 existUser·p0.999:  21.731 ms/op
                 existUser·p0.9999: 22.472 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16610
  mean =      1.936 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14874 
    [ 2.500,  5.000) = 1664 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.449 ms/op
     p(99.9000) =     21.731 ms/op
     p(99.9900) =     22.472 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 3.180 ±(99.9%) 0.075 ms/op
Iteration   1: 1.905 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   1.761 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   2.678 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  15.798 ms/op
                 getUser·p0.9999: 16.640 ms/op
                 getUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16741
  mean =      1.905 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 791 
    [ 1.250,  2.500) = 14558 
    [ 2.500,  3.750) = 1167 
    [ 3.750,  5.000) = 139 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.678 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =     15.798 ms/op
     p(99.9900) =     16.640 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


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
# Warmup Iteration   1: 4.852 ±(99.9%) 0.265 ms/op
Iteration   1: 3.372 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   3.068 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.645 ms/op
                 listUser·p0.999:  13.083 ms/op
                 listUser·p0.9999: 13.287 ms/op
                 listUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9472
  mean =      3.372 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 116 
    [ 2.500,  3.750) = 6791 
    [ 3.750,  5.000) = 2376 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.645 ms/op
     p(99.9000) =     13.083 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.070          ops/ms
ClientSimple.existUser                       thrpt         12.431          ops/ms
ClientSimple.getUser                         thrpt         13.425          ops/ms
ClientSimple.listUser                        thrpt          8.335          ops/ms
ClientSimple.createUser                       avgt          2.369           ms/op
ClientSimple.existUser                        avgt          1.869           ms/op
ClientSimple.getUser                          avgt          1.772           ms/op
ClientSimple.listUser                         avgt          3.159           ms/op
ClientSimple.createUser                     sample  13968   2.294 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.602           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.050           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.785           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.185           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.306           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.696           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.206           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.219           ms/op
ClientSimple.existUser                      sample  16610   1.936 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.462           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.712           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.732           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.449           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.731           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.472           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.905           ms/op
ClientSimple.getUser                        sample  16741   1.905 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.585           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.761           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.678           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.473           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.798           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.640           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.728           ms/op
ClientSimple.listUser                       sample   9472   3.372 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.534           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.068           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.645           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.083           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.287           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.287           ms/op

Benchmark result is saved to 1722818683735.json
