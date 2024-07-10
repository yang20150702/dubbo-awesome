# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.600 ops/ms
Iteration   1: 5.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.936 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.798 ops/ms
Iteration   1: 11.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.519 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.755 ops/ms
Iteration   1: 12.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.970 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.636 ops/ms
Iteration   1: 8.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.702 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ±(99.9%) 0.061 ms/op
Iteration   1: 2.263 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.263 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.432 ±(99.9%) 0.067 ms/op
Iteration   1: 1.892 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.892 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.384 ±(99.9%) 0.066 ms/op
Iteration   1: 2.173 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.173 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.655 ±(99.9%) 0.113 ms/op
Iteration   1: 3.499 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.499 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.645 ±(99.9%) 0.106 ms/op
Iteration   1: 2.251 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   1.915 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.338 ms/op
                 createUser·p0.99:   11.950 ms/op
                 createUser·p0.999:  20.972 ms/op
                 createUser·p0.9999: 22.469 ms/op
                 createUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14360
  mean =      2.251 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11477 
    [ 2.500,  5.000) = 2522 
    [ 5.000,  7.500) = 137 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.338 ms/op
     p(99.0000) =     11.950 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     22.469 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.120 ±(99.9%) 0.076 ms/op
Iteration   1: 2.047 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.597 ms/op
                 existUser·p0.95:   2.862 ms/op
                 existUser·p0.99:   5.274 ms/op
                 existUser·p0.999:  11.213 ms/op
                 existUser·p0.9999: 11.602 ms/op
                 existUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15624
  mean =      2.047 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 539 
    [ 1.250,  2.500) = 12956 
    [ 2.500,  3.750) = 1836 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 114 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.862 ms/op
     p(99.0000) =      5.274 ms/op
     p(99.9000) =     11.213 ms/op
     p(99.9900) =     11.602 ms/op
     p(99.9990) =     11.731 ms/op
     p(99.9999) =     11.731 ms/op
    p(100.0000) =     11.731 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.212 ±(99.9%) 0.082 ms/op
Iteration   1: 1.899 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.449 ms/op
                 getUser·p0.50:   1.763 ms/op
                 getUser·p0.90:   2.101 ms/op
                 getUser·p0.95:   2.286 ms/op
                 getUser·p0.99:   4.462 ms/op
                 getUser·p0.999:  22.491 ms/op
                 getUser·p0.9999: 24.202 ms/op
                 getUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16813
  mean =      1.899 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16284 
    [ 2.500,  5.000) = 371 
    [ 5.000,  7.500) = 58 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      1.763 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      4.462 ms/op
     p(99.9000) =     22.491 ms/op
     p(99.9900) =     24.202 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.585 ±(99.9%) 0.144 ms/op
Iteration   1: 3.414 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.142 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.729 ms/op
                 listUser·p0.999:  25.329 ms/op
                 listUser·p0.9999: 26.214 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9509
  mean =      3.414 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 499 
    [ 2.500,  5.000) = 8766 
    [ 5.000,  7.500) = 190 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.729 ms/op
     p(99.9000) =     25.329 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     26.214 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.936          ops/ms
ClientSimple.existUser                       thrpt         11.519          ops/ms
ClientSimple.getUser                         thrpt         12.970          ops/ms
ClientSimple.listUser                        thrpt          8.702          ops/ms
ClientSimple.createUser                       avgt          2.263           ms/op
ClientSimple.existUser                        avgt          1.892           ms/op
ClientSimple.getUser                          avgt          2.173           ms/op
ClientSimple.listUser                         avgt          3.499           ms/op
ClientSimple.createUser                     sample  14360   2.251 ± 0.049   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.526           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.915           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.338           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.950           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.972           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.469           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.741           ms/op
ClientSimple.existUser                      sample  15624   2.047 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.538           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.862           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.274           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.213           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.602           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.731           ms/op
ClientSimple.getUser                        sample  16813   1.899 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.449           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.763           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.101           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.286           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.462           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.491           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.202           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.314           ms/op
ClientSimple.listUser                       sample   9509   3.414 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.108           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.142           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.729           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.329           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.214           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.214           ms/op

Benchmark result is saved to 1720613835038.json
