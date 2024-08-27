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
# Warmup Iteration   1: 1.907 ops/ms
Iteration   1: 7.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.217 ops/ms


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
# Warmup Iteration   1: 6.637 ops/ms
Iteration   1: 12.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.231 ops/ms


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
# Warmup Iteration   1: 6.543 ops/ms
Iteration   1: 13.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.001 ops/ms


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
# Warmup Iteration   1: 5.829 ops/ms
Iteration   1: 9.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.165 ops/ms


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
# Warmup Iteration   1: 4.516 ±(99.9%) 0.103 ms/op
Iteration   1: 2.377 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.377 ms/op


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
# Warmup Iteration   1: 3.114 ±(99.9%) 0.051 ms/op
Iteration   1: 1.867 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.867 ms/op


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
# Warmup Iteration   1: 3.366 ±(99.9%) 0.055 ms/op
Iteration   1: 1.944 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.944 ms/op


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.071 ms/op
Iteration   1: 3.748 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.748 ms/op


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.081 ms/op
Iteration   1: 2.230 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.867 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.872 ms/op
                 createUser·p0.999:  19.204 ms/op
                 createUser·p0.9999: 20.079 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14641
  mean =      2.230 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11262 
    [ 2.500,  5.000) = 3313 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.872 ms/op
     p(99.9000) =     19.204 ms/op
     p(99.9900) =     20.079 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 2.978 ±(99.9%) 0.062 ms/op
Iteration   1: 2.031 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.342 ms/op
                 existUser·p0.50:   1.919 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  25.765 ms/op
                 existUser·p0.9999: 26.542 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15725
  mean =      2.031 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14551 
    [ 2.500,  5.000) = 1022 
    [ 5.000,  7.500) = 25 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =     25.765 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 3.412 ±(99.9%) 0.077 ms/op
Iteration   1: 2.025 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   1.896 ms/op
                 getUser·p0.90:   2.490 ms/op
                 getUser·p0.95:   2.646 ms/op
                 getUser·p0.99:   3.186 ms/op
                 getUser·p0.999:  13.435 ms/op
                 getUser·p0.9999: 13.707 ms/op
                 getUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15925
  mean =      2.025 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 14297 
    [ 2.500,  3.750) = 1446 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.490 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      3.186 ms/op
     p(99.9000) =     13.435 ms/op
     p(99.9900) =     13.707 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 4.263 ±(99.9%) 0.127 ms/op
Iteration   1: 3.255 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.117 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  6.816 ms/op
                 listUser·p0.9999: 9.454 ms/op
                 listUser·p1.00:   9.454 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9870
  mean =      3.255 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 193 
    [ 2.000,  3.000) = 4296 
    [ 3.000,  4.000) = 4028 
    [ 4.000,  5.000) = 1157 
    [ 5.000,  6.000) = 105 
    [ 6.000,  7.000) = 84 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      6.816 ms/op
     p(99.9900) =      9.454 ms/op
     p(99.9990) =      9.454 ms/op
     p(99.9999) =      9.454 ms/op
    p(100.0000) =      9.454 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.217          ops/ms
ClientSimple.existUser                       thrpt         12.231          ops/ms
ClientSimple.getUser                         thrpt         13.001          ops/ms
ClientSimple.listUser                        thrpt          9.165          ops/ms
ClientSimple.createUser                       avgt          2.377           ms/op
ClientSimple.existUser                        avgt          1.867           ms/op
ClientSimple.getUser                          avgt          1.944           ms/op
ClientSimple.listUser                         avgt          3.748           ms/op
ClientSimple.createUser                     sample  14641   2.230 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.790           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.105           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.872           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.204           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.079           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.185           ms/op
ClientSimple.existUser                      sample  15725   2.031 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.342           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.694           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.765           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.542           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.673           ms/op
ClientSimple.getUser                        sample  15925   2.025 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.602           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.896           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.646           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.186           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.435           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.707           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.746           ms/op
ClientSimple.listUser                       sample   9870   3.255 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.946           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.117           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.125           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.734           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.816           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.454           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.454           ms/op

Benchmark result is saved to 1724782388971.json
