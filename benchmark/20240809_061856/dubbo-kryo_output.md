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
# Warmup Iteration   1: 1.085 ops/ms
Iteration   1: 6.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.311 ops/ms


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
# Warmup Iteration   1: 6.033 ops/ms
Iteration   1: 12.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.182 ops/ms


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
# Warmup Iteration   1: 5.789 ops/ms
Iteration   1: 14.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.071 ops/ms


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
# Warmup Iteration   1: 5.269 ops/ms
Iteration   1: 8.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.891 ops/ms


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.071 ms/op
Iteration   1: 2.134 ±(99.9%) 0.021 ms/op


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
# Warmup Iteration   1: 2.978 ±(99.9%) 0.041 ms/op
Iteration   1: 2.000 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.000 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.069 ms/op
Iteration   1: 1.924 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.924 ms/op


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
# Warmup Iteration   1: 4.647 ±(99.9%) 0.113 ms/op
Iteration   1: 3.573 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.573 ms/op


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
# Warmup Iteration   1: 3.588 ±(99.9%) 0.087 ms/op
Iteration   1: 2.039 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.593 ms/op
                 createUser·p0.50:   1.855 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   2.928 ms/op
                 createUser·p0.99:   7.247 ms/op
                 createUser·p0.999:  16.421 ms/op
                 createUser·p0.9999: 18.125 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15740
  mean =      2.039 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 546 
    [ 1.250,  2.500) = 13546 
    [ 2.500,  3.750) = 1168 
    [ 3.750,  5.000) = 166 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.928 ms/op
     p(99.0000) =      7.247 ms/op
     p(99.9000) =     16.421 ms/op
     p(99.9900) =     18.125 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.194 ±(99.9%) 0.079 ms/op
Iteration   1: 1.870 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   1.765 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.445 ms/op
                 existUser·p0.99:   3.944 ms/op
                 existUser·p0.999:  12.858 ms/op
                 existUser·p0.9999: 13.716 ms/op
                 existUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17102
  mean =      1.870 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 482 
    [ 1.250,  2.500) = 15871 
    [ 2.500,  3.750) = 540 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =     12.858 ms/op
     p(99.9900) =     13.716 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.076 ms/op
Iteration   1: 2.122 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   2.017 ms/op
                 getUser·p0.90:   2.507 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.798 ms/op
                 getUser·p0.999:  11.435 ms/op
                 getUser·p0.9999: 12.919 ms/op
                 getUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15073
  mean =      2.122 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 13458 
    [ 2.500,  3.750) = 1393 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 62 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.798 ms/op
     p(99.9000) =     11.435 ms/op
     p(99.9900) =     12.919 ms/op
     p(99.9990) =     12.927 ms/op
     p(99.9999) =     12.927 ms/op
    p(100.0000) =     12.927 ms/op


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
# Warmup Iteration   1: 4.483 ±(99.9%) 0.179 ms/op
Iteration   1: 3.147 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.226 ms/op
                 listUser·p0.999:  15.644 ms/op
                 listUser·p0.9999: 18.322 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10166
  mean =      3.147 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 450 
    [ 2.500,  3.750) = 8248 
    [ 3.750,  5.000) = 1297 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     15.644 ms/op
     p(99.9900) =     18.322 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.311          ops/ms
ClientSimple.existUser                       thrpt         12.182          ops/ms
ClientSimple.getUser                         thrpt         14.071          ops/ms
ClientSimple.listUser                        thrpt          8.891          ops/ms
ClientSimple.createUser                       avgt          2.134           ms/op
ClientSimple.existUser                        avgt          2.000           ms/op
ClientSimple.getUser                          avgt          1.924           ms/op
ClientSimple.listUser                         avgt          3.573           ms/op
ClientSimple.createUser                     sample  15740   2.039 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.593           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.855           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.928           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.247           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.421           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.125           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.219           ms/op
ClientSimple.existUser                      sample  17102   1.870 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.590           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.765           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.944           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.858           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.716           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.844           ms/op
ClientSimple.getUser                        sample  15073   2.122 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.773           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.017           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.798           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.435           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.919           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.927           ms/op
ClientSimple.listUser                       sample  10166   3.147 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.237           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.908           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.961           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.226           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.644           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.322           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.350           ms/op

Benchmark result is saved to 1723184073719.json
