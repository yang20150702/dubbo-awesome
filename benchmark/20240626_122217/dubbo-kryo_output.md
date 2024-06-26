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
# Warmup Iteration   1: 0.672 ops/ms
Iteration   1: 5.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.694 ops/ms


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
# Warmup Iteration   1: 4.808 ops/ms
Iteration   1: 12.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.989 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.597 ops/ms
Iteration   1: 12.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.800 ops/ms


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
# Warmup Iteration   1: 5.055 ops/ms
Iteration   1: 8.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.524 ops/ms


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.067 ms/op
Iteration   1: 2.167 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.167 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.054 ms/op
Iteration   1: 2.039 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.039 ms/op


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
# Warmup Iteration   1: 3.493 ±(99.9%) 0.085 ms/op
Iteration   1: 2.178 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.178 ms/op


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
# Warmup Iteration   1: 4.482 ±(99.9%) 0.099 ms/op
Iteration   1: 3.359 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.359 ms/op


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
# Warmup Iteration   1: 3.488 ±(99.9%) 0.076 ms/op
Iteration   1: 2.275 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.092 ms/op
                 createUser·p0.90:   2.660 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   8.625 ms/op
                 createUser·p0.999:  20.414 ms/op
                 createUser·p0.9999: 21.712 ms/op
                 createUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14056
  mean =      2.275 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11366 
    [ 2.500,  5.000) = 2431 
    [ 5.000,  7.500) = 88 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.092 ms/op
     p(90.0000) =      2.660 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      8.625 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     21.712 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 2.872 ±(99.9%) 0.061 ms/op
Iteration   1: 1.977 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.436 ms/op
                 existUser·p0.50:   1.944 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   3.646 ms/op
                 existUser·p0.999:  21.654 ms/op
                 existUser·p0.9999: 21.803 ms/op
                 existUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16177
  mean =      1.977 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15490 
    [ 2.500,  5.000) = 603 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      3.646 ms/op
     p(99.9000) =     21.654 ms/op
     p(99.9900) =     21.803 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.086 ms/op
Iteration   1: 1.970 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   1.927 ms/op
                 getUser·p0.90:   2.404 ms/op
                 getUser·p0.95:   2.634 ms/op
                 getUser·p0.99:   3.391 ms/op
                 getUser·p0.999:  12.028 ms/op
                 getUser·p0.9999: 12.422 ms/op
                 getUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16412
  mean =      1.970 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 150 
    [ 1.250,  2.500) = 15087 
    [ 2.500,  3.750) = 1087 
    [ 3.750,  5.000) = 21 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      1.927 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      3.391 ms/op
     p(99.9000) =     12.028 ms/op
     p(99.9900) =     12.422 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


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
# Warmup Iteration   1: 4.784 ±(99.9%) 0.229 ms/op
Iteration   1: 3.650 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.478 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   6.393 ms/op
                 listUser·p0.999:  12.554 ms/op
                 listUser·p0.9999: 14.729 ms/op
                 listUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8761
  mean =      3.650 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 464 
    [ 2.500,  3.750) = 4441 
    [ 3.750,  5.000) = 3346 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.393 ms/op
     p(99.9000) =     12.554 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     14.729 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.694          ops/ms
ClientSimple.existUser                       thrpt         12.989          ops/ms
ClientSimple.getUser                         thrpt         12.800          ops/ms
ClientSimple.listUser                        thrpt          8.524          ops/ms
ClientSimple.createUser                       avgt          2.167           ms/op
ClientSimple.existUser                        avgt          2.039           ms/op
ClientSimple.getUser                          avgt          2.178           ms/op
ClientSimple.listUser                         avgt          3.359           ms/op
ClientSimple.createUser                     sample  14056   2.275 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.570           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.092           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.660           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.625           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.414           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.712           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.725           ms/op
ClientSimple.existUser                      sample  16177   1.977 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.436           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.944           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.646           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.654           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.803           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.823           ms/op
ClientSimple.getUser                        sample  16412   1.970 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.868           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.927           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.404           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.634           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.391           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.028           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.422           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.632           ms/op
ClientSimple.listUser                       sample   8761   3.650 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.029           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.478           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.071           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.393           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.554           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.729           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.729           ms/op

Benchmark result is saved to 1719404285447.json
