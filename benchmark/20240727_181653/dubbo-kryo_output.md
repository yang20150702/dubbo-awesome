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
# Warmup Iteration   1: 1.685 ops/ms
Iteration   1: 7.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.362 ops/ms


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
# Warmup Iteration   1: 6.069 ops/ms
Iteration   1: 11.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.880 ops/ms


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
# Warmup Iteration   1: 5.618 ops/ms
Iteration   1: 13.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.324 ops/ms


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
# Warmup Iteration   1: 5.065 ops/ms
Iteration   1: 9.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.204 ops/ms


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
# Warmup Iteration   1: 4.919 ±(99.9%) 0.117 ms/op
Iteration   1: 2.147 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.147 ms/op


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
# Warmup Iteration   1: 3.076 ±(99.9%) 0.054 ms/op
Iteration   1: 1.868 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.868 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.065 ms/op
Iteration   1: 1.975 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.975 ms/op


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
# Warmup Iteration   1: 5.074 ±(99.9%) 0.109 ms/op
Iteration   1: 3.248 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.248 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.086 ms/op
Iteration   1: 2.244 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.032 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  26.804 ms/op
                 createUser·p0.9999: 28.977 ms/op
                 createUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14249
  mean =      2.244 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10338 
    [ 2.500,  5.000) = 3771 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 19 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      4.686 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     28.977 ms/op
     p(99.9990) =     29.032 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 2.806 ±(99.9%) 0.062 ms/op
Iteration   1: 1.842 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  11.872 ms/op
                 existUser·p0.9999: 15.579 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17350
  mean =      1.842 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 473 
    [ 1.250,  2.500) = 16074 
    [ 2.500,  3.750) = 619 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =     11.872 ms/op
     p(99.9900) =     15.579 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.537 ±(99.9%) 0.101 ms/op
Iteration   1: 2.306 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.146 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.289 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  10.547 ms/op
                 getUser·p0.9999: 10.643 ms/op
                 getUser·p1.00:   10.650 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14257
  mean =      2.306 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 22 
    [ 1.000,  2.000) = 4769 
    [ 2.000,  3.000) = 8093 
    [ 3.000,  4.000) = 1037 
    [ 4.000,  5.000) = 168 
    [ 5.000,  6.000) = 101 
    [ 6.000,  7.000) = 30 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     10.547 ms/op
     p(99.9900) =     10.643 ms/op
     p(99.9990) =     10.650 ms/op
     p(99.9999) =     10.650 ms/op
    p(100.0000) =     10.650 ms/op


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
# Warmup Iteration   1: 5.160 ±(99.9%) 0.157 ms/op
Iteration   1: 3.319 ±(99.9%) 0.062 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.682 ms/op
                 listUser·p0.999:  31.666 ms/op
                 listUser·p0.9999: 32.178 ms/op
                 listUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9620
  mean =      3.319 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 992 
    [ 2.500,  5.000) = 8356 
    [ 5.000,  7.500) = 176 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.682 ms/op
     p(99.9000) =     31.666 ms/op
     p(99.9900) =     32.178 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.362          ops/ms
ClientSimple.existUser                       thrpt         11.880          ops/ms
ClientSimple.getUser                         thrpt         13.324          ops/ms
ClientSimple.listUser                        thrpt          9.204          ops/ms
ClientSimple.createUser                       avgt          2.147           ms/op
ClientSimple.existUser                        avgt          1.868           ms/op
ClientSimple.getUser                          avgt          1.975           ms/op
ClientSimple.listUser                         avgt          3.248           ms/op
ClientSimple.createUser                     sample  14249   2.244 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.790           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.032           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.011           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.195           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.686           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.804           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.977           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.032           ms/op
ClientSimple.existUser                      sample  17350   1.842 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.524           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.729           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.208           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.276           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.872           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.579           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.892           ms/op
ClientSimple.getUser                        sample  14257   2.306 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.690           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.146           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.986           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.289           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.128           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.547           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.643           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.650           ms/op
ClientSimple.listUser                       sample   9620   3.319 ± 0.062   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.895           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.006           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.497           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.682           ms/op
ClientSimple.listUser:listUser·p0.999       sample         31.666           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.178           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.178           ms/op

Benchmark result is saved to 1722103955455.json
