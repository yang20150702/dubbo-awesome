# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.784 ops/ms
Iteration   1: 6.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.880 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.879 ops/ms
Iteration   1: 12.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.223 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.436 ops/ms
Iteration   1: 12.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.577 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.906 ops/ms
Iteration   1: 7.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.929 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.680 ±(99.9%) 0.059 ms/op
Iteration   1: 2.136 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.136 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.266 ±(99.9%) 0.063 ms/op
Iteration   1: 1.974 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.739 ±(99.9%) 0.072 ms/op
Iteration   1: 2.343 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.343 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.693 ±(99.9%) 0.115 ms/op
Iteration   1: 3.533 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.797 ±(99.9%) 0.090 ms/op
Iteration   1: 2.015 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   1.835 ms/op
                 createUser·p0.90:   2.347 ms/op
                 createUser·p0.95:   2.535 ms/op
                 createUser·p0.99:   12.337 ms/op
                 createUser·p0.999:  21.561 ms/op
                 createUser·p0.9999: 30.160 ms/op
                 createUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15874
  mean =      2.015 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14982 
    [ 2.500,  5.000) = 715 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =     12.337 ms/op
     p(99.9000) =     21.561 ms/op
     p(99.9900) =     30.160 ms/op
     p(99.9990) =     30.179 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.490 ±(99.9%) 0.086 ms/op
Iteration   1: 1.935 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.362 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   3.331 ms/op
                 existUser·p0.999:  30.522 ms/op
                 existUser·p0.9999: 31.021 ms/op
                 existUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16536
  mean =      1.935 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15628 
    [ 2.500,  5.000) = 771 
    [ 5.000,  7.500) = 62 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 8 
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
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.331 ms/op
     p(99.9000) =     30.522 ms/op
     p(99.9900) =     31.021 ms/op
     p(99.9990) =     31.064 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.838 ±(99.9%) 0.113 ms/op
Iteration   1: 2.133 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   2.017 ms/op
                 getUser·p0.90:   2.580 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  13.255 ms/op
                 getUser·p0.9999: 13.476 ms/op
                 getUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14991
  mean =      2.133 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 12835 
    [ 2.500,  3.750) = 1919 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     13.476 ms/op
     p(99.9990) =     13.484 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.548 ±(99.9%) 0.151 ms/op
Iteration   1: 3.220 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.841 ms/op
                 listUser·p0.999:  13.894 ms/op
                 listUser·p0.9999: 14.336 ms/op
                 listUser·p1.00:   14.336 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9927
  mean =      3.220 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1526 
    [ 2.500,  3.750) = 6082 
    [ 3.750,  5.000) = 2153 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.880          ops/ms
ClientSimple.existUser                       thrpt         12.223          ops/ms
ClientSimple.getUser                         thrpt         12.577          ops/ms
ClientSimple.listUser                        thrpt          7.929          ops/ms
ClientSimple.createUser                       avgt          2.136           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.343           ms/op
ClientSimple.listUser                         avgt          3.533           ms/op
ClientSimple.createUser                     sample  15874   2.015 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.672           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.835           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.347           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.535           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.337           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.561           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.160           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.179           ms/op
ClientSimple.existUser                      sample  16536   1.935 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.362           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.331           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.522           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.021           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.064           ms/op
ClientSimple.getUser                        sample  14991   2.133 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.770           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.017           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.342           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.255           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.476           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.484           ms/op
ClientSimple.listUser                       sample   9927   3.220 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.046           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.998           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.841           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.894           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.336           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.336           ms/op

Benchmark result is saved to 1711735818792.json
