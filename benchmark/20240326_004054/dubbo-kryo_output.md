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
# Warmup Iteration   1: 2.019 ops/ms
Iteration   1: 7.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.206 ops/ms


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
# Warmup Iteration   1: 6.298 ops/ms
Iteration   1: 13.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.391 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.392 ops/ms
Iteration   1: 14.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.833 ops/ms


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
# Warmup Iteration   1: 5.787 ops/ms
Iteration   1: 8.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.664 ops/ms


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.081 ms/op
Iteration   1: 2.280 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.280 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.076 ms/op
Iteration   1: 1.878 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.878 ms/op


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
# Warmup Iteration   1: 3.380 ±(99.9%) 0.061 ms/op
Iteration   1: 2.019 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.019 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.392 ±(99.9%) 0.092 ms/op
Iteration   1: 3.305 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.305 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.108 ms/op
Iteration   1: 2.022 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   1.827 ms/op
                 createUser·p0.90:   2.302 ms/op
                 createUser·p0.95:   2.545 ms/op
                 createUser·p0.99:   8.168 ms/op
                 createUser·p0.999:  22.184 ms/op
                 createUser·p0.9999: 25.247 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15814
  mean =      2.022 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14945 
    [ 2.500,  5.000) = 655 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.545 ms/op
     p(99.0000) =      8.168 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     25.247 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.082 ms/op
Iteration   1: 1.860 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   1.786 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.216 ms/op
                 existUser·p0.999:  11.466 ms/op
                 existUser·p0.9999: 12.079 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17189
  mean =      1.860 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 622 
    [ 1.250,  2.500) = 15611 
    [ 2.500,  3.750) = 843 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.786 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.216 ms/op
     p(99.9000) =     11.466 ms/op
     p(99.9900) =     12.079 ms/op
     p(99.9990) =     12.173 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.075 ms/op
Iteration   1: 2.002 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.458 ms/op
                 getUser·p0.50:   1.759 ms/op
                 getUser·p0.90:   2.724 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  24.543 ms/op
                 getUser·p0.9999: 24.707 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15999
  mean =      2.002 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13825 
    [ 2.500,  5.000) = 2076 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.458 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =     24.543 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 5.051 ±(99.9%) 0.171 ms/op
Iteration   1: 3.770 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.103 ms/op
                 listUser·p0.999:  20.333 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8480
  mean =      3.770 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 386 
    [ 2.500,  5.000) = 7841 
    [ 5.000,  7.500) = 188 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     20.333 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.206          ops/ms
ClientSimple.existUser                       thrpt         13.391          ops/ms
ClientSimple.getUser                         thrpt         14.833          ops/ms
ClientSimple.listUser                        thrpt          8.664          ops/ms
ClientSimple.createUser                       avgt          2.280           ms/op
ClientSimple.existUser                        avgt          1.878           ms/op
ClientSimple.getUser                          avgt          2.019           ms/op
ClientSimple.listUser                         avgt          3.305           ms/op
ClientSimple.createUser                     sample  15814   2.022 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.616           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.827           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.302           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.545           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.168           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.184           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.247           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.952           ms/op
ClientSimple.existUser                      sample  17189   1.860 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.564           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.786           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.216           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.466           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.079           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.173           ms/op
ClientSimple.getUser                        sample  15999   2.002 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.458           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.759           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.109           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.678           ms/op
ClientSimple.getUser:getUser·p0.999         sample         24.543           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.707           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.805           ms/op
ClientSimple.listUser                       sample   8480   3.770 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.380           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.719           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.103           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.333           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.398           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.398           ms/op

Benchmark result is saved to 1711413415700.json
