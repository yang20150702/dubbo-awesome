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
# Warmup Iteration   1: 2.171 ops/ms
Iteration   1: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.349 ops/ms


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
# Warmup Iteration   1: 5.475 ops/ms
Iteration   1: 12.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.633 ops/ms


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
# Warmup Iteration   1: 5.119 ops/ms
Iteration   1: 12.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.013 ops/ms


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
# Warmup Iteration   1: 5.072 ops/ms
Iteration   1: 8.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.679 ops/ms


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
# Warmup Iteration   1: 3.582 ±(99.9%) 0.063 ms/op
Iteration   1: 2.209 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.209 ms/op


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
# Warmup Iteration   1: 3.310 ±(99.9%) 0.060 ms/op
Iteration   1: 1.826 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.826 ms/op


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
# Warmup Iteration   1: 3.422 ±(99.9%) 0.064 ms/op
Iteration   1: 2.055 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.055 ms/op


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.084 ms/op
Iteration   1: 3.053 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.053 ms/op


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
# Warmup Iteration   1: 3.174 ±(99.9%) 0.080 ms/op
Iteration   1: 2.050 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   1.837 ms/op
                 createUser·p0.90:   2.343 ms/op
                 createUser·p0.95:   2.572 ms/op
                 createUser·p0.99:   11.682 ms/op
                 createUser·p0.999:  24.597 ms/op
                 createUser·p0.9999: 25.100 ms/op
                 createUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15586
  mean =      2.050 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14617 
    [ 2.500,  5.000) = 728 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     24.597 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


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
# Warmup Iteration   1: 3.045 ±(99.9%) 0.065 ms/op
Iteration   1: 1.601 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   1.503 ms/op
                 existUser·p0.90:   2.034 ms/op
                 existUser·p0.95:   2.232 ms/op
                 existUser·p0.99:   2.650 ms/op
                 existUser·p0.999:  21.038 ms/op
                 existUser·p0.9999: 21.168 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19961
  mean =      1.601 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19696 
    [ 2.500,  5.000) = 210 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      1.503 ms/op
     p(90.0000) =      2.034 ms/op
     p(95.0000) =      2.232 ms/op
     p(99.0000) =      2.650 ms/op
     p(99.9000) =     21.038 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.102 ms/op
Iteration   1: 1.883 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.348 ms/op
                 getUser·p0.50:   1.745 ms/op
                 getUser·p0.90:   2.335 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  17.467 ms/op
                 getUser·p0.9999: 22.132 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16972
  mean =      1.883 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15983 
    [ 2.500,  5.000) = 926 
    [ 5.000,  7.500) = 31 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.348 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =     17.467 ms/op
     p(99.9900) =     22.132 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 4.412 ±(99.9%) 0.129 ms/op
Iteration   1: 3.478 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   0.754 ms/op
                 listUser·p0.50:   3.371 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.583 ms/op
                 listUser·p0.99:   7.264 ms/op
                 listUser·p0.999:  24.504 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9209
  mean =      3.478 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 942 
    [ 2.500,  5.000) = 7951 
    [ 5.000,  7.500) = 230 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.583 ms/op
     p(99.0000) =      7.264 ms/op
     p(99.9000) =     24.504 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.349          ops/ms
ClientSimple.existUser                       thrpt         12.633          ops/ms
ClientSimple.getUser                         thrpt         12.013          ops/ms
ClientSimple.listUser                        thrpt          8.679          ops/ms
ClientSimple.createUser                       avgt          2.209           ms/op
ClientSimple.existUser                        avgt          1.826           ms/op
ClientSimple.getUser                          avgt          2.055           ms/op
ClientSimple.listUser                         avgt          3.053           ms/op
ClientSimple.createUser                     sample  15586   2.050 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.651           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.837           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.343           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.682           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.597           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.100           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.100           ms/op
ClientSimple.existUser                      sample  19961   1.601 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.570           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.503           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.034           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.038           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.168           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.168           ms/op
ClientSimple.getUser                        sample  16972   1.883 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.348           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.745           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.335           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.715           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.467           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.132           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.805           ms/op
ClientSimple.listUser                       sample   9209   3.478 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.754           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.371           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.583           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.264           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.504           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.707           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.707           ms/op

Benchmark result is saved to 1724436767900.json
