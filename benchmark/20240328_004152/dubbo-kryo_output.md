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
# Warmup Iteration   1: 0.955 ops/ms
Iteration   1: 6.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.054 ops/ms


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
# Warmup Iteration   1: 6.029 ops/ms
Iteration   1: 11.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.813 ops/ms


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
# Warmup Iteration   1: 5.729 ops/ms
Iteration   1: 13.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.554 ops/ms


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
# Warmup Iteration   1: 6.298 ops/ms
Iteration   1: 8.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.948 ops/ms


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.091 ms/op
Iteration   1: 2.375 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.375 ms/op


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
# Warmup Iteration   1: 3.501 ±(99.9%) 0.052 ms/op
Iteration   1: 1.973 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.973 ms/op


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
# Warmup Iteration   1: 3.423 ±(99.9%) 0.061 ms/op
Iteration   1: 2.172 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.172 ms/op


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
# Warmup Iteration   1: 4.578 ±(99.9%) 0.096 ms/op
Iteration   1: 3.469 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.469 ms/op


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
# Warmup Iteration   1: 3.490 ±(99.9%) 0.090 ms/op
Iteration   1: 2.307 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.550 ms/op
                 createUser·p0.50:   2.122 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   6.929 ms/op
                 createUser·p0.999:  24.082 ms/op
                 createUser·p0.9999: 26.938 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13844
  mean =      2.307 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11097 
    [ 2.500,  5.000) = 2527 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      6.929 ms/op
     p(99.9000) =     24.082 ms/op
     p(99.9900) =     26.938 ms/op
     p(99.9990) =     27.001 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 2.922 ±(99.9%) 0.067 ms/op
Iteration   1: 1.954 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.404 ms/op
                 existUser·p0.50:   1.837 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   4.333 ms/op
                 existUser·p0.999:  26.883 ms/op
                 existUser·p0.9999: 27.570 ms/op
                 existUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16601
  mean =      1.954 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15686 
    [ 2.500,  5.000) = 796 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      4.333 ms/op
     p(99.9000) =     26.883 ms/op
     p(99.9900) =     27.570 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.092 ms/op
Iteration   1: 2.171 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.773 ms/op
                 getUser·p0.95:   2.953 ms/op
                 getUser·p0.99:   3.573 ms/op
                 getUser·p0.999:  11.239 ms/op
                 getUser·p0.9999: 12.013 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14856
  mean =      2.171 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 302 
    [ 1.250,  2.500) = 11213 
    [ 2.500,  3.750) = 3214 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      3.573 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     12.013 ms/op
     p(99.9990) =     12.141 ms/op
     p(99.9999) =     12.141 ms/op
    p(100.0000) =     12.141 ms/op


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.119 ms/op
Iteration   1: 3.515 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   3.482 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  20.349 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9101
  mean =      3.515 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 795 
    [ 2.500,  5.000) = 7985 
    [ 5.000,  7.500) = 250 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.054          ops/ms
ClientSimple.existUser                       thrpt         11.813          ops/ms
ClientSimple.getUser                         thrpt         13.554          ops/ms
ClientSimple.listUser                        thrpt          8.948          ops/ms
ClientSimple.createUser                       avgt          2.375           ms/op
ClientSimple.existUser                        avgt          1.973           ms/op
ClientSimple.getUser                          avgt          2.172           ms/op
ClientSimple.listUser                         avgt          3.469           ms/op
ClientSimple.createUser                     sample  13844   2.307 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.550           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.122           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.084           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.929           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.082           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.938           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.001           ms/op
ClientSimple.existUser                      sample  16601   1.954 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.404           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.837           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.333           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.883           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.570           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.656           ms/op
ClientSimple.getUser                        sample  14856   2.171 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.515           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.953           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.573           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.239           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.013           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.141           ms/op
ClientSimple.listUser                       sample   9101   3.515 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.971           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.482           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.242           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.349           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.742           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.742           ms/op

Benchmark result is saved to 1711586223372.json
