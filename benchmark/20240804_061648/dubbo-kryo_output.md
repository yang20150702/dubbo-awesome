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
# Warmup Iteration   1: 1.959 ops/ms
Iteration   1: 7.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.063 ops/ms


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
# Warmup Iteration   1: 5.683 ops/ms
Iteration   1: 12.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.376 ops/ms


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
# Warmup Iteration   1: 5.668 ops/ms
Iteration   1: 13.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.248 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.108 ops/ms
Iteration   1: 8.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.667 ops/ms


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
# Warmup Iteration   1: 3.701 ±(99.9%) 0.066 ms/op
Iteration   1: 2.140 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.140 ms/op


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
# Warmup Iteration   1: 2.936 ±(99.9%) 0.047 ms/op
Iteration   1: 1.852 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.852 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.046 ms/op
Iteration   1: 1.888 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.888 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.097 ms/op
Iteration   1: 3.320 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.320 ms/op


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
# Warmup Iteration   1: 3.355 ±(99.9%) 0.069 ms/op
Iteration   1: 2.017 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   1.769 ms/op
                 createUser·p0.90:   2.425 ms/op
                 createUser·p0.95:   2.740 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  26.968 ms/op
                 createUser·p0.9999: 31.811 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16066
  mean =      2.017 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14724 
    [ 2.500,  5.000) = 1174 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     26.968 ms/op
     p(99.9900) =     31.811 ms/op
     p(99.9990) =     31.850 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.745 ±(99.9%) 0.054 ms/op
Iteration   1: 1.702 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.443 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   1.906 ms/op
                 existUser·p0.95:   2.093 ms/op
                 existUser·p0.99:   2.992 ms/op
                 existUser·p0.999:  14.303 ms/op
                 existUser·p0.9999: 14.682 ms/op
                 existUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18814
  mean =      1.702 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 553 
    [ 1.250,  2.500) = 17896 
    [ 2.500,  3.750) = 248 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.443 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      1.906 ms/op
     p(95.0000) =      2.093 ms/op
     p(99.0000) =      2.992 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     14.682 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.081 ±(99.9%) 0.079 ms/op
Iteration   1: 2.305 ±(99.9%) 0.088 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   2.064 ms/op
                 getUser·p0.90:   2.740 ms/op
                 getUser·p0.95:   2.949 ms/op
                 getUser·p0.99:   4.259 ms/op
                 getUser·p0.999:  67.052 ms/op
                 getUser·p0.9999: 67.713 ms/op
                 getUser·p1.00:   67.764 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13869
  mean =      2.305 ±(99.9%) 0.088 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13763 
    [ 5.000, 10.000) = 3 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      4.259 ms/op
     p(99.9000) =     67.052 ms/op
     p(99.9900) =     67.713 ms/op
     p(99.9990) =     67.764 ms/op
     p(99.9999) =     67.764 ms/op
    p(100.0000) =     67.764 ms/op


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
# Warmup Iteration   1: 4.803 ±(99.9%) 0.138 ms/op
Iteration   1: 3.314 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.289 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.170 ms/op
                 listUser·p0.99:   6.564 ms/op
                 listUser·p0.999:  10.315 ms/op
                 listUser·p0.9999: 11.076 ms/op
                 listUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9673
  mean =      3.314 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 1087 
    [ 2.500,  3.750) = 6557 
    [ 3.750,  5.000) = 1812 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.564 ms/op
     p(99.9000) =     10.315 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     11.076 ms/op
     p(99.9999) =     11.076 ms/op
    p(100.0000) =     11.076 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.063          ops/ms
ClientSimple.existUser                       thrpt         12.376          ops/ms
ClientSimple.getUser                         thrpt         13.248          ops/ms
ClientSimple.listUser                        thrpt          8.667          ops/ms
ClientSimple.createUser                       avgt          2.140           ms/op
ClientSimple.existUser                        avgt          1.852           ms/op
ClientSimple.getUser                          avgt          1.888           ms/op
ClientSimple.listUser                         avgt          3.320           ms/op
ClientSimple.createUser                     sample  16066   2.017 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.750           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.769           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.425           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.439           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.968           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.811           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.850           ms/op
ClientSimple.existUser                      sample  18814   1.702 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.443           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.638           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.906           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.093           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.992           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.303           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.682           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.696           ms/op
ClientSimple.getUser                        sample  13869   2.305 ± 0.088   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.591           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.064           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.259           ms/op
ClientSimple.getUser:getUser·p0.999         sample         67.052           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         67.713           ms/op
ClientSimple.getUser:getUser·p1.00          sample         67.764           ms/op
ClientSimple.listUser                       sample   9673   3.314 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.049           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.289           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.981           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.170           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.564           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.315           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         11.076           ms/op
ClientSimple.listUser:listUser·p1.00        sample         11.076           ms/op

Benchmark result is saved to 1722751948828.json
