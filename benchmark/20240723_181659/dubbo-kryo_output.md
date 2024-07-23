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
# Warmup Iteration   1: 1.039 ops/ms
Iteration   1: 5.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.026 ops/ms


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
# Warmup Iteration   1: 5.612 ops/ms
Iteration   1: 12.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.373 ops/ms


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
# Warmup Iteration   1: 5.403 ops/ms
Iteration   1: 11.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.465 ops/ms


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
# Warmup Iteration   1: 3.979 ops/ms
Iteration   1: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.229 ops/ms


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.077 ms/op
Iteration   1: 2.134 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.134 ms/op


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
# Warmup Iteration   1: 3.429 ±(99.9%) 0.087 ms/op
Iteration   1: 2.070 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.070 ms/op


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
# Warmup Iteration   1: 3.251 ±(99.9%) 0.057 ms/op
Iteration   1: 2.133 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.133 ms/op


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
# Warmup Iteration   1: 4.794 ±(99.9%) 0.103 ms/op
Iteration   1: 3.718 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.718 ms/op


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
# Warmup Iteration   1: 3.441 ±(99.9%) 0.080 ms/op
Iteration   1: 2.049 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   1.894 ms/op
                 createUser·p0.90:   2.413 ms/op
                 createUser·p0.95:   2.699 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  19.792 ms/op
                 createUser·p0.9999: 20.543 ms/op
                 createUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15599
  mean =      2.049 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14378 
    [ 2.500,  5.000) = 1021 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     20.543 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 2.949 ±(99.9%) 0.076 ms/op
Iteration   1: 1.906 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.657 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.478 ms/op
                 existUser·p0.95:   2.745 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  14.385 ms/op
                 existUser·p0.9999: 14.478 ms/op
                 existUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16795
  mean =      1.906 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 270 
    [ 1.250,  2.500) = 14898 
    [ 2.500,  3.750) = 1406 
    [ 3.750,  5.000) = 145 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.745 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     14.478 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.100 ms/op
Iteration   1: 2.057 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.445 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   5.752 ms/op
                 getUser·p0.999:  20.409 ms/op
                 getUser·p0.9999: 22.187 ms/op
                 getUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15560
  mean =      2.057 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14293 
    [ 2.500,  5.000) = 1089 
    [ 5.000,  7.500) = 99 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      5.752 ms/op
     p(99.9000) =     20.409 ms/op
     p(99.9900) =     22.187 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.118 ms/op
Iteration   1: 3.630 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   12.439 ms/op
                 listUser·p0.999:  23.433 ms/op
                 listUser·p0.9999: 25.035 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8880
  mean =      3.630 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1196 
    [ 2.500,  5.000) = 7392 
    [ 5.000,  7.500) = 169 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =     12.439 ms/op
     p(99.9000) =     23.433 ms/op
     p(99.9900) =     25.035 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.026          ops/ms
ClientSimple.existUser                       thrpt         12.373          ops/ms
ClientSimple.getUser                         thrpt         11.465          ops/ms
ClientSimple.listUser                        thrpt          8.229          ops/ms
ClientSimple.createUser                       avgt          2.134           ms/op
ClientSimple.existUser                        avgt          2.070           ms/op
ClientSimple.getUser                          avgt          2.133           ms/op
ClientSimple.listUser                         avgt          3.718           ms/op
ClientSimple.createUser                     sample  15599   2.049 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.633           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.894           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.413           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.699           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.291           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.792           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.543           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.873           ms/op
ClientSimple.existUser                      sample  16795   1.906 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.657           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.745           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.745           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.202           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.385           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.478           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.500           ms/op
ClientSimple.getUser                        sample  15560   2.057 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.670           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.752           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.409           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.187           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.315           ms/op
ClientSimple.listUser                       sample   8880   3.630 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.814           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.506           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.497           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.439           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.433           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.035           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.035           ms/op

Benchmark result is saved to 1721758360361.json
