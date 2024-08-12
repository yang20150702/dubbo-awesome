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
# Warmup Iteration   1: 1.688 ops/ms
Iteration   1: 6.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.950 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.613 ops/ms
Iteration   1: 11.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.575 ops/ms


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
# Warmup Iteration   1: 5.561 ops/ms
Iteration   1: 12.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.556 ops/ms


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
# Warmup Iteration   1: 4.717 ops/ms
Iteration   1: 7.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.904 ops/ms


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
# Warmup Iteration   1: 4.318 ±(99.9%) 0.078 ms/op
Iteration   1: 2.265 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.265 ms/op


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
# Warmup Iteration   1: 3.086 ±(99.9%) 0.069 ms/op
Iteration   1: 1.817 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.817 ms/op


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
# Warmup Iteration   1: 3.518 ±(99.9%) 0.069 ms/op
Iteration   1: 2.102 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.102 ms/op


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
# Warmup Iteration   1: 4.061 ±(99.9%) 0.062 ms/op
Iteration   1: 3.724 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.724 ms/op


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
# Warmup Iteration   1: 3.657 ±(99.9%) 0.092 ms/op
Iteration   1: 2.389 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.296 ms/op
                 createUser·p0.50:   2.261 ms/op
                 createUser·p0.90:   2.736 ms/op
                 createUser·p0.95:   2.929 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  19.759 ms/op
                 createUser·p0.9999: 20.633 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13375
  mean =      2.389 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10124 
    [ 2.500,  5.000) = 3024 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.296 ms/op
     p(50.0000) =      2.261 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     20.633 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 3.024 ±(99.9%) 0.063 ms/op
Iteration   1: 1.797 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   2.118 ms/op
                 existUser·p0.95:   2.372 ms/op
                 existUser·p0.99:   3.035 ms/op
                 existUser·p0.999:  17.241 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17855
  mean =      1.797 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 17165 
    [ 2.500,  3.750) = 512 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      3.035 ms/op
     p(99.9000) =     17.241 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.250 ±(99.9%) 0.069 ms/op
Iteration   1: 1.817 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.366 ms/op
                 getUser·p0.50:   1.681 ms/op
                 getUser·p0.90:   2.286 ms/op
                 getUser·p0.95:   2.478 ms/op
                 getUser·p0.99:   3.444 ms/op
                 getUser·p0.999:  11.705 ms/op
                 getUser·p0.9999: 12.568 ms/op
                 getUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17613
  mean =      1.817 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 461 
    [ 1.250,  2.500) = 16336 
    [ 2.500,  3.750) = 696 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.366 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.444 ms/op
     p(99.9000) =     11.705 ms/op
     p(99.9900) =     12.568 ms/op
     p(99.9990) =     12.993 ms/op
     p(99.9999) =     12.993 ms/op
    p(100.0000) =     12.993 ms/op


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.133 ms/op
Iteration   1: 3.713 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.190 ms/op
                 listUser·p0.999:  8.935 ms/op
                 listUser·p0.9999: 9.011 ms/op
                 listUser·p1.00:   9.011 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8634
  mean =      3.713 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 6 
    [ 1.500,  2.000) = 42 
    [ 2.000,  2.500) = 163 
    [ 2.500,  3.000) = 1296 
    [ 3.000,  3.500) = 1455 
    [ 3.500,  4.000) = 3088 
    [ 4.000,  4.500) = 1778 
    [ 4.500,  5.000) = 531 
    [ 5.000,  5.500) = 144 
    [ 5.500,  6.000) = 28 
    [ 6.000,  6.500) = 43 
    [ 6.500,  7.000) = 35 
    [ 7.000,  7.500) = 11 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 13 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.190 ms/op
     p(99.9000) =      8.935 ms/op
     p(99.9900) =      9.011 ms/op
     p(99.9990) =      9.011 ms/op
     p(99.9999) =      9.011 ms/op
    p(100.0000) =      9.011 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.950          ops/ms
ClientSimple.existUser                       thrpt         11.575          ops/ms
ClientSimple.getUser                         thrpt         12.556          ops/ms
ClientSimple.listUser                        thrpt          7.904          ops/ms
ClientSimple.createUser                       avgt          2.265           ms/op
ClientSimple.existUser                        avgt          1.817           ms/op
ClientSimple.getUser                          avgt          2.102           ms/op
ClientSimple.listUser                         avgt          3.724           ms/op
ClientSimple.createUser                     sample  13375   2.389 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.296           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.261           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.736           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.306           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.759           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.633           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.644           ms/op
ClientSimple.existUser                      sample  17855   1.797 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.884           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.679           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.035           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.241           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.400           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.400           ms/op
ClientSimple.getUser                        sample  17613   1.817 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.366           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.681           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.286           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.444           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.705           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.568           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.993           ms/op
ClientSimple.listUser                       sample   8634   3.713 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.374           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.748           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.190           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.935           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.011           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.011           ms/op

Benchmark result is saved to 1723423500048.json
