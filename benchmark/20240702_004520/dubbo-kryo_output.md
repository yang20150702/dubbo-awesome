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
# Warmup Iteration   1: 1.587 ops/ms
Iteration   1: 7.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.125 ops/ms


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
# Warmup Iteration   1: 6.480 ops/ms
Iteration   1: 11.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.408 ops/ms


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
# Warmup Iteration   1: 5.190 ops/ms
Iteration   1: 12.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.698 ops/ms


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
# Warmup Iteration   1: 5.236 ops/ms
Iteration   1: 8.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.586 ops/ms


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.074 ms/op
Iteration   1: 2.270 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.270 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.055 ms/op
Iteration   1: 1.960 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.960 ms/op


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
# Warmup Iteration   1: 3.188 ±(99.9%) 0.053 ms/op
Iteration   1: 1.996 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.996 ms/op


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.098 ms/op
Iteration   1: 3.595 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.595 ms/op


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.092 ms/op
Iteration   1: 2.064 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   1.876 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.638 ms/op
                 createUser·p0.99:   4.022 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 17.793 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15500
  mean =      2.064 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 13773 
    [ 2.500,  3.750) = 1488 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 2.922 ±(99.9%) 0.080 ms/op
Iteration   1: 1.835 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.435 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.375 ms/op
                 existUser·p0.999:  17.072 ms/op
                 existUser·p0.9999: 17.170 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17415
  mean =      1.835 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 489 
    [ 1.250,  2.500) = 16166 
    [ 2.500,  3.750) = 620 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.375 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.080 ms/op
Iteration   1: 2.145 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.458 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   3.330 ms/op
                 getUser·p0.999:  11.583 ms/op
                 getUser·p0.9999: 12.001 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14912
  mean =      2.145 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 149 
    [ 1.250,  2.500) = 11972 
    [ 2.500,  3.750) = 2692 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.330 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     12.001 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


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
# Warmup Iteration   1: 6.183 ±(99.9%) 0.160 ms/op
Iteration   1: 3.720 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  16.056 ms/op
                 listUser·p0.9999: 16.384 ms/op
                 listUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8599
  mean =      3.720 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 591 
    [ 2.500,  3.750) = 4135 
    [ 3.750,  5.000) = 3494 
    [ 5.000,  6.250) = 163 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     16.384 ms/op
     p(99.9990) =     16.384 ms/op
     p(99.9999) =     16.384 ms/op
    p(100.0000) =     16.384 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.125          ops/ms
ClientSimple.existUser                       thrpt         11.408          ops/ms
ClientSimple.getUser                         thrpt         12.698          ops/ms
ClientSimple.listUser                        thrpt          8.586          ops/ms
ClientSimple.createUser                       avgt          2.270           ms/op
ClientSimple.existUser                        avgt          1.960           ms/op
ClientSimple.getUser                          avgt          1.996           ms/op
ClientSimple.listUser                         avgt          3.595           ms/op
ClientSimple.createUser                     sample  15500   2.064 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.744           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.876           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.022           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.236           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.793           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.793           ms/op
ClientSimple.existUser                      sample  17415   1.835 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.435           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.708           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.241           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.375           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.072           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.170           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.170           ms/op
ClientSimple.getUser                        sample  14912   2.145 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.458           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.330           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.583           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.001           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.009           ms/op
ClientSimple.listUser                       sample   8599   3.720 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.300           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.654           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.882           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.126           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.056           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.384           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.384           ms/op

Benchmark result is saved to 1719880883053.json
