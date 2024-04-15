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
# Warmup Iteration   1: 0.741 ops/ms
Iteration   1: 6.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.170 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.782 ops/ms
Iteration   1: 14.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.916 ops/ms


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
# Warmup Iteration   1: 6.218 ops/ms
Iteration   1: 16.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  16.317 ops/ms


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
# Warmup Iteration   1: 5.735 ops/ms
Iteration   1: 8.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.762 ops/ms


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.088 ms/op
Iteration   1: 2.282 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.282 ms/op


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
# Warmup Iteration   1: 3.380 ±(99.9%) 0.049 ms/op
Iteration   1: 1.830 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.830 ms/op


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
# Warmup Iteration   1: 3.244 ±(99.9%) 0.058 ms/op
Iteration   1: 2.088 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.088 ms/op


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
# Warmup Iteration   1: 4.640 ±(99.9%) 0.095 ms/op
Iteration   1: 3.629 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.629 ms/op


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
# Warmup Iteration   1: 3.687 ±(99.9%) 0.117 ms/op
Iteration   1: 2.270 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.510 ms/op
                 createUser·p0.50:   1.995 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.785 ms/op
                 createUser·p0.99:   11.848 ms/op
                 createUser·p0.999:  22.776 ms/op
                 createUser·p0.9999: 29.036 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14187
  mean =      2.270 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12271 
    [ 2.500,  5.000) = 1653 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =     11.848 ms/op
     p(99.9000) =     22.776 ms/op
     p(99.9900) =     29.036 ms/op
     p(99.9990) =     29.393 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 2.867 ±(99.9%) 0.062 ms/op
Iteration   1: 1.892 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   1.757 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   4.022 ms/op
                 existUser·p0.999:  18.907 ms/op
                 existUser·p0.9999: 18.940 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16900
  mean =      1.892 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 553 
    [ 1.250,  2.500) = 15359 
    [ 2.500,  3.750) = 795 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 3.135 ±(99.9%) 0.077 ms/op
Iteration   1: 2.279 ±(99.9%) 0.085 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.028 ms/op
                 getUser·p0.90:   2.744 ms/op
                 getUser·p0.95:   2.982 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  65.250 ms/op
                 getUser·p0.9999: 70.531 ms/op
                 getUser·p1.00:   72.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14362
  mean =      2.279 ±(99.9%) 0.085 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14180 
    [ 5.000, 10.000) = 118 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 12 
    [65.000, 70.000) = 19 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     65.250 ms/op
     p(99.9900) =     70.531 ms/op
     p(99.9990) =     72.876 ms/op
     p(99.9999) =     72.876 ms/op
    p(100.0000) =     72.876 ms/op


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.115 ms/op
Iteration   1: 3.613 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.081 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  21.122 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8853
  mean =      3.613 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 313 
    [ 2.500,  5.000) = 8354 
    [ 5.000,  7.500) = 148 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     21.122 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.170          ops/ms
ClientSimple.existUser                       thrpt         14.916          ops/ms
ClientSimple.getUser                         thrpt         16.317          ops/ms
ClientSimple.listUser                        thrpt          8.762          ops/ms
ClientSimple.createUser                       avgt          2.282           ms/op
ClientSimple.existUser                        avgt          1.830           ms/op
ClientSimple.getUser                          avgt          2.088           ms/op
ClientSimple.listUser                         avgt          3.629           ms/op
ClientSimple.createUser                     sample  14187   2.270 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.510           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.995           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.785           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.848           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.776           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.036           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.393           ms/op
ClientSimple.existUser                      sample  16900   1.892 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.641           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.757           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.560           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.022           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.907           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.940           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.940           ms/op
ClientSimple.getUser                        sample  14362   2.279 ± 0.085   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.826           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.028           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.982           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.612           ms/op
ClientSimple.getUser:getUser·p0.999         sample         65.250           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         70.531           ms/op
ClientSimple.getUser:getUser·p1.00          sample         72.876           ms/op
ClientSimple.listUser                       sample   8853   3.613 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.081           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.539           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.275           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.122           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.708           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.708           ms/op

Benchmark result is saved to 1713150384945.json
