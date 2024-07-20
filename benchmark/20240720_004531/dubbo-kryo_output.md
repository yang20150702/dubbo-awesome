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
# Warmup Iteration   1: 2.063 ops/ms
Iteration   1: 6.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.877 ops/ms


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
# Warmup Iteration   1: 5.967 ops/ms
Iteration   1: 14.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.164 ops/ms


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
# Warmup Iteration   1: 5.557 ops/ms
Iteration   1: 13.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.532 ops/ms


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
# Warmup Iteration   1: 5.220 ops/ms
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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.085 ms/op
Iteration   1: 2.332 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.332 ms/op


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
# Warmup Iteration   1: 3.632 ±(99.9%) 0.062 ms/op
Iteration   1: 2.159 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.159 ms/op


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
# Warmup Iteration   1: 3.434 ±(99.9%) 0.058 ms/op
Iteration   1: 1.952 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.952 ms/op


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
# Warmup Iteration   1: 4.753 ±(99.9%) 0.099 ms/op
Iteration   1: 3.336 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.336 ms/op


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.094 ms/op
Iteration   1: 2.112 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   1.784 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.995 ms/op
                 createUser·p0.99:   9.732 ms/op
                 createUser·p0.999:  13.959 ms/op
                 createUser·p0.9999: 17.367 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15196
  mean =      2.112 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 211 
    [ 1.250,  2.500) = 12952 
    [ 2.500,  3.750) = 1489 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.995 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.070 ms/op
Iteration   1: 1.890 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.306 ms/op
                 existUser·p0.95:   2.408 ms/op
                 existUser·p0.99:   2.855 ms/op
                 existUser·p0.999:  15.584 ms/op
                 existUser·p0.9999: 15.729 ms/op
                 existUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16905
  mean =      1.890 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 603 
    [ 1.250,  2.500) = 15838 
    [ 2.500,  3.750) = 398 
    [ 3.750,  5.000) = 2 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      2.855 ms/op
     p(99.9000) =     15.584 ms/op
     p(99.9900) =     15.729 ms/op
     p(99.9990) =     15.729 ms/op
     p(99.9999) =     15.729 ms/op
    p(100.0000) =     15.729 ms/op


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
# Warmup Iteration   1: 3.407 ±(99.9%) 0.077 ms/op
Iteration   1: 2.300 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.034 ms/op
                 getUser·p0.50:   2.167 ms/op
                 getUser·p0.90:   2.793 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  13.207 ms/op
                 getUser·p0.9999: 13.640 ms/op
                 getUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13898
  mean =      2.300 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 10618 
    [ 2.500,  3.750) = 2963 
    [ 3.750,  5.000) = 143 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.793 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =     13.207 ms/op
     p(99.9900) =     13.640 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 5.018 ±(99.9%) 0.293 ms/op
Iteration   1: 3.513 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.647 ms/op
                 listUser·p0.99:   7.001 ms/op
                 listUser·p0.999:  19.748 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9113
  mean =      3.513 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1232 
    [ 2.500,  5.000) = 7565 
    [ 5.000,  7.500) = 249 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.647 ms/op
     p(99.0000) =      7.001 ms/op
     p(99.9000) =     19.748 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.877          ops/ms
ClientSimple.existUser                       thrpt         14.164          ops/ms
ClientSimple.getUser                         thrpt         13.532          ops/ms
ClientSimple.listUser                        thrpt          8.899          ops/ms
ClientSimple.createUser                       avgt          2.332           ms/op
ClientSimple.existUser                        avgt          2.159           ms/op
ClientSimple.getUser                          avgt          1.952           ms/op
ClientSimple.listUser                         avgt          3.336           ms/op
ClientSimple.createUser                     sample  15196   2.112 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.536           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.784           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.995           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.732           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.959           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.367           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.367           ms/op
ClientSimple.existUser                      sample  16905   1.890 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.636           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.306           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.584           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.729           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.729           ms/op
ClientSimple.getUser                        sample  13898   2.300 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.034           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.167           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.088           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.300           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.207           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.640           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.730           ms/op
ClientSimple.listUser                       sample   9113   3.513 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.266           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.551           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.647           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.001           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.748           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.775           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.775           ms/op

Benchmark result is saved to 1721436097352.json
