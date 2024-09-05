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
# Warmup Iteration   1: 1.847 ops/ms
Iteration   1: 6.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.787 ops/ms


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
# Warmup Iteration   1: 4.818 ops/ms
Iteration   1: 12.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.198 ops/ms


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
# Warmup Iteration   1: 5.543 ops/ms
Iteration   1: 11.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.699 ops/ms


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
# Warmup Iteration   1: 4.478 ops/ms
Iteration   1: 8.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.138 ops/ms


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.082 ms/op
Iteration   1: 2.195 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.195 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.082 ms/op
Iteration   1: 2.030 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.030 ms/op


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
# Warmup Iteration   1: 3.522 ±(99.9%) 0.064 ms/op
Iteration   1: 2.269 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.269 ms/op


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
# Warmup Iteration   1: 4.400 ±(99.9%) 0.079 ms/op
Iteration   1: 3.349 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.349 ms/op


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
# Warmup Iteration   1: 3.651 ±(99.9%) 0.098 ms/op
Iteration   1: 2.080 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.740 ms/op
                 createUser·p0.99:   5.663 ms/op
                 createUser·p0.999:  14.658 ms/op
                 createUser·p0.9999: 14.975 ms/op
                 createUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15366
  mean =      2.080 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 122 
    [ 1.250,  2.500) = 13938 
    [ 2.500,  3.750) = 943 
    [ 3.750,  5.000) = 187 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      5.663 ms/op
     p(99.9000) =     14.658 ms/op
     p(99.9900) =     14.975 ms/op
     p(99.9990) =     14.975 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 2.975 ±(99.9%) 0.069 ms/op
Iteration   1: 1.796 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   1.616 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.513 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  29.655 ms/op
                 existUser·p0.9999: 29.892 ms/op
                 existUser·p1.00:   29.917 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17788
  mean =      1.796 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16872 
    [ 2.500,  5.000) = 817 
    [ 5.000,  7.500) = 35 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.616 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.513 ms/op
     p(99.0000) =      4.039 ms/op
     p(99.9000) =     29.655 ms/op
     p(99.9900) =     29.892 ms/op
     p(99.9990) =     29.917 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


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
# Warmup Iteration   1: 3.318 ±(99.9%) 0.083 ms/op
Iteration   1: 2.126 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.058 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.732 ms/op
                 getUser·p0.99:   3.336 ms/op
                 getUser·p0.999:  12.131 ms/op
                 getUser·p0.9999: 12.566 ms/op
                 getUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15143
  mean =      2.126 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 12936 
    [ 2.500,  3.750) = 2012 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.336 ms/op
     p(99.9000) =     12.131 ms/op
     p(99.9900) =     12.566 ms/op
     p(99.9990) =     12.583 ms/op
     p(99.9999) =     12.583 ms/op
    p(100.0000) =     12.583 ms/op


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
# Warmup Iteration   1: 4.458 ±(99.9%) 0.149 ms/op
Iteration   1: 3.264 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.964 ms/op
                 listUser·p0.999:  7.058 ms/op
                 listUser·p0.9999: 10.060 ms/op
                 listUser·p1.00:   10.060 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9792
  mean =      3.264 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 19 
    [ 2.000,  3.000) = 4560 
    [ 3.000,  4.000) = 3883 
    [ 4.000,  5.000) = 1123 
    [ 5.000,  6.000) = 113 
    [ 6.000,  7.000) = 79 
    [ 7.000,  8.000) = 12 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =      7.058 ms/op
     p(99.9900) =     10.060 ms/op
     p(99.9990) =     10.060 ms/op
     p(99.9999) =     10.060 ms/op
    p(100.0000) =     10.060 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.787          ops/ms
ClientSimple.existUser                       thrpt         12.198          ops/ms
ClientSimple.getUser                         thrpt         11.699          ops/ms
ClientSimple.listUser                        thrpt          8.138          ops/ms
ClientSimple.createUser                       avgt          2.195           ms/op
ClientSimple.existUser                        avgt          2.030           ms/op
ClientSimple.getUser                          avgt          2.269           ms/op
ClientSimple.listUser                         avgt          3.349           ms/op
ClientSimple.createUser                     sample  15366   2.080 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.712           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.663           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.658           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.975           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.975           ms/op
ClientSimple.existUser                      sample  17788   1.796 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.518           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.616           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.513           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.039           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.655           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         29.892           ms/op
ClientSimple.existUser:existUser·p1.00      sample         29.917           ms/op
ClientSimple.getUser                        sample  15143   2.126 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.800           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.058           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.336           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.131           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.566           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.583           ms/op
ClientSimple.listUser                       sample   9792   3.264 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.280           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.964           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.058           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.060           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.060           ms/op

Benchmark result is saved to 1725538714313.json
