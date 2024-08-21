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
# Warmup Iteration   1: 1.883 ops/ms
Iteration   1: 7.087 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.087 ops/ms


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
# Warmup Iteration   1: 5.454 ops/ms
Iteration   1: 10.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.772 ops/ms


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
Iteration   1: 13.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.244 ops/ms


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
# Warmup Iteration   1: 5.771 ops/ms
Iteration   1: 8.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.402 ops/ms


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
# Warmup Iteration   1: 4.426 ±(99.9%) 0.097 ms/op
Iteration   1: 2.219 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.219 ms/op


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
# Warmup Iteration   1: 3.457 ±(99.9%) 0.047 ms/op
Iteration   1: 1.650 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.650 ms/op


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
# Warmup Iteration   1: 3.248 ±(99.9%) 0.067 ms/op
Iteration   1: 2.042 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.085 ms/op
Iteration   1: 3.389 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.389 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.106 ms/op
Iteration   1: 2.123 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   1.911 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.920 ms/op
                 createUser·p0.99:   7.672 ms/op
                 createUser·p0.999:  25.199 ms/op
                 createUser·p0.9999: 25.931 ms/op
                 createUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15201
  mean =      2.123 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12962 
    [ 2.500,  5.000) = 1987 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      7.672 ms/op
     p(99.9000) =     25.199 ms/op
     p(99.9900) =     25.931 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.077 ms/op
Iteration   1: 1.823 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   1.692 ms/op
                 existUser·p0.90:   2.191 ms/op
                 existUser·p0.95:   2.375 ms/op
                 existUser·p0.99:   3.209 ms/op
                 existUser·p0.999:  13.320 ms/op
                 existUser·p0.9999: 13.431 ms/op
                 existUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17544
  mean =      1.823 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 16845 
    [ 2.500,  3.750) = 433 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.191 ms/op
     p(95.0000) =      2.375 ms/op
     p(99.0000) =      3.209 ms/op
     p(99.9000) =     13.320 ms/op
     p(99.9900) =     13.431 ms/op
     p(99.9990) =     13.468 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


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
# Warmup Iteration   1: 3.274 ±(99.9%) 0.076 ms/op
Iteration   1: 1.930 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.409 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.425 ms/op
                 getUser·p0.95:   2.609 ms/op
                 getUser·p0.99:   3.236 ms/op
                 getUser·p0.999:  11.624 ms/op
                 getUser·p0.9999: 11.682 ms/op
                 getUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16534
  mean =      1.930 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 165 
    [ 1.250,  2.500) = 15122 
    [ 2.500,  3.750) = 1159 
    [ 3.750,  5.000) = 24 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.409 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.236 ms/op
     p(99.9000) =     11.624 ms/op
     p(99.9900) =     11.682 ms/op
     p(99.9990) =     11.682 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.115 ms/op
Iteration   1: 3.786 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8449
  mean =      3.786 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 943 
    [ 2.500,  3.750) = 3049 
    [ 3.750,  5.000) = 3803 
    [ 5.000,  6.250) = 512 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     18.907 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.087          ops/ms
ClientSimple.existUser                       thrpt         10.772          ops/ms
ClientSimple.getUser                         thrpt         13.244          ops/ms
ClientSimple.listUser                        thrpt          8.402          ops/ms
ClientSimple.createUser                       avgt          2.219           ms/op
ClientSimple.existUser                        avgt          1.650           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.389           ms/op
ClientSimple.createUser                     sample  15201   2.123 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.683           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.911           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.920           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.672           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.199           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.931           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.477           ms/op
ClientSimple.existUser                      sample  17544   1.823 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.519           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.692           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.191           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.375           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.209           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.320           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.431           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.468           ms/op
ClientSimple.getUser                        sample  16534   1.930 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.409           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.425           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.236           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.624           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.682           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.682           ms/op
ClientSimple.listUser                       sample   8449   3.786 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.877           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.292           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.963           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.269           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.907           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.907           ms/op

Benchmark result is saved to 1724263982103.json
