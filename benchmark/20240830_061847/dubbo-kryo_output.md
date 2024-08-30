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
# Warmup Iteration   1: 1.317 ops/ms
Iteration   1: 6.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.711 ops/ms


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
# Warmup Iteration   1: 5.299 ops/ms
Iteration   1: 10.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.977 ops/ms


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
# Warmup Iteration   1: 6.237 ops/ms
Iteration   1: 13.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.761 ops/ms


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
# Warmup Iteration   1: 5.392 ops/ms
Iteration   1: 9.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.116 ops/ms


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.062 ms/op
Iteration   1: 1.932 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.932 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.054 ms/op
Iteration   1: 2.284 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.284 ms/op


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
# Warmup Iteration   1: 3.122 ±(99.9%) 0.048 ms/op
Iteration   1: 2.218 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.218 ms/op


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.082 ms/op
Iteration   1: 3.268 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.268 ms/op


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.160 ms/op
Iteration   1: 2.714 ±(99.9%) 0.106 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.355 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.534 ms/op
                 createUser·p0.99:   9.732 ms/op
                 createUser·p0.999:  69.992 ms/op
                 createUser·p0.9999: 78.096 ms/op
                 createUser·p1.00:   78.119 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11784
  mean =      2.714 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11478 
    [ 5.000, 10.000) = 193 
    [10.000, 15.000) = 68 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 5 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 14 
    [70.000, 75.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.355 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.534 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     69.992 ms/op
     p(99.9900) =     78.096 ms/op
     p(99.9990) =     78.119 ms/op
     p(99.9999) =     78.119 ms/op
    p(100.0000) =     78.119 ms/op


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
# Warmup Iteration   1: 3.042 ±(99.9%) 0.082 ms/op
Iteration   1: 1.863 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.220 ms/op
                 existUser·p0.95:   2.413 ms/op
                 existUser·p0.99:   3.035 ms/op
                 existUser·p0.999:  11.805 ms/op
                 existUser·p0.9999: 11.944 ms/op
                 existUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17488
  mean =      1.863 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 16759 
    [ 2.500,  3.750) = 482 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      3.035 ms/op
     p(99.9000) =     11.805 ms/op
     p(99.9900) =     11.944 ms/op
     p(99.9990) =     12.042 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


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
# Warmup Iteration   1: 3.574 ±(99.9%) 0.099 ms/op
Iteration   1: 2.116 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.537 ms/op
                 getUser·p0.50:   1.980 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.793 ms/op
                 getUser·p0.99:   4.059 ms/op
                 getUser·p0.999:  12.272 ms/op
                 getUser·p0.9999: 16.300 ms/op
                 getUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15100
  mean =      2.116 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 190 
    [ 1.250,  2.500) = 13139 
    [ 2.500,  3.750) = 1555 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =     12.272 ms/op
     p(99.9900) =     16.300 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.232 ms/op
Iteration   1: 3.549 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  24.412 ms/op
                 listUser·p0.9999: 25.657 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9015
  mean =      3.549 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1007 
    [ 2.500,  5.000) = 7860 
    [ 5.000,  7.500) = 116 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     24.412 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.711          ops/ms
ClientSimple.existUser                       thrpt         10.977          ops/ms
ClientSimple.getUser                         thrpt         13.761          ops/ms
ClientSimple.listUser                        thrpt          9.116          ops/ms
ClientSimple.createUser                       avgt          1.932           ms/op
ClientSimple.existUser                        avgt          2.284           ms/op
ClientSimple.getUser                          avgt          2.218           ms/op
ClientSimple.listUser                         avgt          3.268           ms/op
ClientSimple.createUser                     sample  11784   2.714 ± 0.106   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.856           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.355           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.534           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.732           ms/op
ClientSimple.createUser:createUser·p0.999   sample         69.992           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         78.096           ms/op
ClientSimple.createUser:createUser·p1.00    sample         78.119           ms/op
ClientSimple.existUser                      sample  17488   1.863 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.583           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.761           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.035           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.805           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.944           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.042           ms/op
ClientSimple.getUser                        sample  15100   2.116 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.537           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.980           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.793           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.059           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.272           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.300           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.417           ms/op
ClientSimple.listUser                       sample   9015   3.549 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.908           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.572           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.317           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.547           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.595           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.412           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.657           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.657           ms/op

Benchmark result is saved to 1724998465651.json
