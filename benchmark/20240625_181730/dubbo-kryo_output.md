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
# Warmup Iteration   1: 1.606 ops/ms
Iteration   1: 7.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.094 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.776 ops/ms
Iteration   1: 12.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.490 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.889 ops/ms
Iteration   1: 13.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.762 ops/ms


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
# Warmup Iteration   1: 3.959 ops/ms
Iteration   1: 8.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.857 ops/ms


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.069 ms/op
Iteration   1: 2.245 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.245 ms/op


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
# Warmup Iteration   1: 3.612 ±(99.9%) 0.063 ms/op
Iteration   1: 1.921 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.921 ms/op


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
# Warmup Iteration   1: 3.319 ±(99.9%) 0.059 ms/op
Iteration   1: 1.762 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.762 ms/op


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
# Warmup Iteration   1: 6.299 ±(99.9%) 0.139 ms/op
Iteration   1: 3.675 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.675 ms/op


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
# Warmup Iteration   1: 3.693 ±(99.9%) 0.090 ms/op
Iteration   1: 2.377 ±(99.9%) 0.070 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   2.085 ms/op
                 createUser·p0.90:   2.747 ms/op
                 createUser·p0.95:   3.067 ms/op
                 createUser·p0.99:   11.862 ms/op
                 createUser·p0.999:  47.090 ms/op
                 createUser·p0.9999: 48.605 ms/op
                 createUser·p1.00:   48.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13462
  mean =      2.377 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13179 
    [ 5.000, 10.000) = 115 
    [10.000, 15.000) = 66 
    [15.000, 20.000) = 64 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.085 ms/op
     p(90.0000) =      2.747 ms/op
     p(95.0000) =      3.067 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     47.090 ms/op
     p(99.9900) =     48.605 ms/op
     p(99.9990) =     48.628 ms/op
     p(99.9999) =     48.628 ms/op
    p(100.0000) =     48.628 ms/op


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.101 ms/op
Iteration   1: 2.059 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.019 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.691 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  11.682 ms/op
                 existUser·p0.9999: 11.813 ms/op
                 existUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15524
  mean =      2.059 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 314 
    [ 1.250,  2.500) = 13825 
    [ 2.500,  3.750) = 1192 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     11.682 ms/op
     p(99.9900) =     11.813 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 3.409 ±(99.9%) 0.083 ms/op
Iteration   1: 2.248 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   2.091 ms/op
                 getUser·p0.90:   2.871 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 13.192 ms/op
                 getUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14221
  mean =      2.248 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 9815 
    [ 2.500,  3.750) = 4057 
    [ 3.750,  5.000) = 142 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.091 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.192 ms/op
     p(99.9990) =     13.206 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.156 ms/op
Iteration   1: 3.322 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.172 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   5.913 ms/op
                 listUser·p0.999:  7.126 ms/op
                 listUser·p0.9999: 7.610 ms/op
                 listUser·p1.00:   7.610 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9618
  mean =      3.322 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 101 
    [2.000, 2.500) = 380 
    [2.500, 3.000) = 3465 
    [3.000, 3.500) = 2217 
    [3.500, 4.000) = 1986 
    [4.000, 4.500) = 823 
    [4.500, 5.000) = 327 
    [5.000, 5.500) = 137 
    [5.500, 6.000) = 84 
    [6.000, 6.500) = 66 
    [6.500, 7.000) = 6 
    [7.000, 7.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.172 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.913 ms/op
     p(99.9000) =      7.126 ms/op
     p(99.9900) =      7.610 ms/op
     p(99.9990) =      7.610 ms/op
     p(99.9999) =      7.610 ms/op
    p(100.0000) =      7.610 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.094          ops/ms
ClientSimple.existUser                       thrpt         12.490          ops/ms
ClientSimple.getUser                         thrpt         13.762          ops/ms
ClientSimple.listUser                        thrpt          8.857          ops/ms
ClientSimple.createUser                       avgt          2.245           ms/op
ClientSimple.existUser                        avgt          1.921           ms/op
ClientSimple.getUser                          avgt          1.762           ms/op
ClientSimple.listUser                         avgt          3.675           ms/op
ClientSimple.createUser                     sample  13462   2.377 ± 0.070   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.857           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.085           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.747           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.067           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.862           ms/op
ClientSimple.createUser:createUser·p0.999   sample         47.090           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         48.605           ms/op
ClientSimple.createUser:createUser·p1.00    sample         48.628           ms/op
ClientSimple.existUser                      sample  15524   2.059 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.899           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.019           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.691           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.424           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.682           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.813           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.813           ms/op
ClientSimple.getUser                        sample  14221   2.248 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.729           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.091           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.076           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.079           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.058           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.192           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.206           ms/op
ClientSimple.listUser                       sample   9618   3.322 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.063           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.172           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.913           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.126           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.610           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.610           ms/op

Benchmark result is saved to 1719339185721.json
