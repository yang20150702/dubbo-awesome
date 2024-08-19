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
# Warmup Iteration   1: 1.716 ops/ms
Iteration   1: 6.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.475 ops/ms


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
# Warmup Iteration   1: 5.859 ops/ms
Iteration   1: 10.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.555 ops/ms


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
# Warmup Iteration   1: 6.092 ops/ms
Iteration   1: 12.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.506 ops/ms


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
# Warmup Iteration   1: 3.992 ops/ms
Iteration   1: 7.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.569 ops/ms


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.070 ms/op
Iteration   1: 2.097 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.097 ms/op


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
# Warmup Iteration   1: 3.505 ±(99.9%) 0.056 ms/op
Iteration   1: 2.075 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.075 ms/op


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
# Warmup Iteration   1: 3.229 ±(99.9%) 0.050 ms/op
Iteration   1: 2.135 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.135 ms/op


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.106 ms/op
Iteration   1: 3.428 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.428 ms/op


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.091 ms/op
Iteration   1: 1.925 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   1.751 ms/op
                 createUser·p0.90:   2.367 ms/op
                 createUser·p0.95:   2.642 ms/op
                 createUser·p0.99:   5.055 ms/op
                 createUser·p0.999:  18.088 ms/op
                 createUser·p0.9999: 20.851 ms/op
                 createUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16605
  mean =      1.925 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15564 
    [ 2.500,  5.000) = 875 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      5.055 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     20.851 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     21.955 ms/op
    p(100.0000) =     21.955 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.098 ms/op
Iteration   1: 1.838 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.372 ms/op
                 existUser·p0.99:   3.924 ms/op
                 existUser·p0.999:  11.624 ms/op
                 existUser·p0.9999: 12.550 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17537
  mean =      1.838 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 471 
    [ 1.250,  2.500) = 16488 
    [ 2.500,  3.750) = 395 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =     11.624 ms/op
     p(99.9900) =     12.550 ms/op
     p(99.9990) =     12.550 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.074 ms/op
Iteration   1: 1.859 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.437 ms/op
                 getUser·p0.50:   1.724 ms/op
                 getUser·p0.90:   2.056 ms/op
                 getUser·p0.95:   2.376 ms/op
                 getUser·p0.99:   3.207 ms/op
                 getUser·p0.999:  30.605 ms/op
                 getUser·p0.9999: 31.077 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17207
  mean =      1.859 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16479 
    [ 2.500,  5.000) = 643 
    [ 5.000,  7.500) = 21 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      1.724 ms/op
     p(90.0000) =      2.056 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      3.207 ms/op
     p(99.9000) =     30.605 ms/op
     p(99.9900) =     31.077 ms/op
     p(99.9990) =     31.195 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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
# Warmup Iteration   1: 4.680 ±(99.9%) 0.190 ms/op
Iteration   1: 3.395 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   3.342 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   5.640 ms/op
                 listUser·p0.999:  8.119 ms/op
                 listUser·p0.9999: 9.306 ms/op
                 listUser·p1.00:   9.306 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9454
  mean =      3.395 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 127 
    [ 2.000,  3.000) = 3332 
    [ 3.000,  4.000) = 4234 
    [ 4.000,  5.000) = 1543 
    [ 5.000,  6.000) = 160 
    [ 6.000,  7.000) = 36 
    [ 7.000,  8.000) = 9 
    [ 8.000,  9.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.640 ms/op
     p(99.9000) =      8.119 ms/op
     p(99.9900) =      9.306 ms/op
     p(99.9990) =      9.306 ms/op
     p(99.9999) =      9.306 ms/op
    p(100.0000) =      9.306 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.475          ops/ms
ClientSimple.existUser                       thrpt         10.555          ops/ms
ClientSimple.getUser                         thrpt         12.506          ops/ms
ClientSimple.listUser                        thrpt          7.569          ops/ms
ClientSimple.createUser                       avgt          2.097           ms/op
ClientSimple.existUser                        avgt          2.075           ms/op
ClientSimple.getUser                          avgt          2.135           ms/op
ClientSimple.listUser                         avgt          3.428           ms/op
ClientSimple.createUser                     sample  16605   1.925 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.723           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.751           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.367           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.055           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.088           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.851           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.955           ms/op
ClientSimple.existUser                      sample  17537   1.838 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.711           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.772           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.924           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.624           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.550           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.550           ms/op
ClientSimple.getUser                        sample  17207   1.859 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.437           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.724           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.056           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.207           ms/op
ClientSimple.getUser:getUser·p0.999         sample         30.605           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         31.077           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.195           ms/op
ClientSimple.listUser                       sample   9454   3.395 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.977           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.342           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.640           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.119           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.306           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.306           ms/op

Benchmark result is saved to 1724048067320.json
