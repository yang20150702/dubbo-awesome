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
# Warmup Iteration   1: 2.054 ops/ms
Iteration   1: 7.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.250 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.540 ops/ms
Iteration   1: 12.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.098 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.330 ops/ms
Iteration   1: 13.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.453 ops/ms


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
# Warmup Iteration   1: 4.365 ops/ms
Iteration   1: 8.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.284 ops/ms


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
# Warmup Iteration   1: 3.693 ±(99.9%) 0.067 ms/op
Iteration   1: 2.220 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.220 ms/op


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
# Warmup Iteration   1: 3.056 ±(99.9%) 0.050 ms/op
Iteration   1: 1.982 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.982 ms/op


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
# Warmup Iteration   1: 3.449 ±(99.9%) 0.063 ms/op
Iteration   1: 1.856 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.856 ms/op


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.081 ms/op
Iteration   1: 3.149 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.149 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.103 ms/op
Iteration   1: 2.377 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   2.212 ms/op
                 createUser·p0.90:   2.855 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  19.759 ms/op
                 createUser·p0.9999: 20.522 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13458
  mean =      2.377 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10295 
    [ 2.500,  5.000) = 2948 
    [ 5.000,  7.500) = 139 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.212 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      6.488 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     20.522 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 3.292 ±(99.9%) 0.112 ms/op
Iteration   1: 1.646 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.625 ms/op
                 existUser·p0.50:   1.470 ms/op
                 existUser·p0.90:   2.162 ms/op
                 existUser·p0.95:   2.556 ms/op
                 existUser·p0.99:   3.120 ms/op
                 existUser·p0.999:  20.873 ms/op
                 existUser·p0.9999: 21.072 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19410
  mean =      1.646 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18251 
    [ 2.500,  5.000) = 1061 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      1.470 ms/op
     p(90.0000) =      2.162 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      3.120 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     21.072 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 3.298 ±(99.9%) 0.086 ms/op
Iteration   1: 2.096 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   1.972 ms/op
                 getUser·p0.90:   2.789 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.914 ms/op
                 getUser·p0.999:  10.259 ms/op
                 getUser·p0.9999: 10.918 ms/op
                 getUser·p1.00:   10.961 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15286
  mean =      2.096 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 12199 
    [ 2.500,  3.750) = 2761 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.914 ms/op
     p(99.9000) =     10.259 ms/op
     p(99.9900) =     10.918 ms/op
     p(99.9990) =     10.961 ms/op
     p(99.9999) =     10.961 ms/op
    p(100.0000) =     10.961 ms/op


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
# Warmup Iteration   1: 4.931 ±(99.9%) 0.136 ms/op
Iteration   1: 3.058 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.079 ms/op
                 listUser·p0.99:   5.139 ms/op
                 listUser·p0.999:  6.924 ms/op
                 listUser·p0.9999: 8.957 ms/op
                 listUser·p1.00:   8.962 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10463
  mean =      3.058 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 45 
    [1.500, 2.000) = 314 
    [2.000, 2.500) = 1117 
    [2.500, 3.000) = 4248 
    [3.000, 3.500) = 2176 
    [3.500, 4.000) = 1960 
    [4.000, 4.500) = 299 
    [4.500, 5.000) = 172 
    [5.000, 5.500) = 55 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 30 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.079 ms/op
     p(99.0000) =      5.139 ms/op
     p(99.9000) =      6.924 ms/op
     p(99.9900) =      8.957 ms/op
     p(99.9990) =      8.962 ms/op
     p(99.9999) =      8.962 ms/op
    p(100.0000) =      8.962 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.250          ops/ms
ClientSimple.existUser                       thrpt         12.098          ops/ms
ClientSimple.getUser                         thrpt         13.453          ops/ms
ClientSimple.listUser                        thrpt          8.284          ops/ms
ClientSimple.createUser                       avgt          2.220           ms/op
ClientSimple.existUser                        avgt          1.982           ms/op
ClientSimple.getUser                          avgt          1.856           ms/op
ClientSimple.listUser                         avgt          3.149           ms/op
ClientSimple.createUser                     sample  13458   2.377 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.720           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.212           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.101           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.488           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.759           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.522           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.578           ms/op
ClientSimple.existUser                      sample  19410   1.646 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.625           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.470           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.162           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.120           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.873           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.072           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.103           ms/op
ClientSimple.getUser                        sample  15286   2.096 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.709           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.972           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.068           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.914           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.259           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.918           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.961           ms/op
ClientSimple.listUser                       sample  10463   3.058 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.020           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.920           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.822           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.079           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.139           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.924           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.957           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.962           ms/op

Benchmark result is saved to 1724523104830.json
