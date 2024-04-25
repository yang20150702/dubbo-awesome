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
# Warmup Iteration   1: 1.569 ops/ms
Iteration   1: 7.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.460 ops/ms


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
# Warmup Iteration   1: 6.291 ops/ms
Iteration   1: 12.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.491 ops/ms


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
# Warmup Iteration   1: 5.900 ops/ms
Iteration   1: 15.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.432 ops/ms


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
# Warmup Iteration   1: 5.335 ops/ms
Iteration   1: 8.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.336 ops/ms


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
# Warmup Iteration   1: 4.036 ±(99.9%) 0.083 ms/op
Iteration   1: 2.247 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.247 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.086 ±(99.9%) 0.040 ms/op
Iteration   1: 1.723 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.723 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.247 ±(99.9%) 0.051 ms/op
Iteration   1: 2.019 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.019 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.768 ±(99.9%) 0.087 ms/op
Iteration   1: 3.251 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.251 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.106 ms/op
Iteration   1: 2.331 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.604 ms/op
                 createUser·p0.50:   2.077 ms/op
                 createUser·p0.90:   2.769 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   8.930 ms/op
                 createUser·p0.999:  25.690 ms/op
                 createUser·p0.9999: 28.042 ms/op
                 createUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13718
  mean =      2.331 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10874 
    [ 2.500,  5.000) = 2596 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.769 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      8.930 ms/op
     p(99.9000) =     25.690 ms/op
     p(99.9900) =     28.042 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.074 ms/op
Iteration   1: 1.952 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.281 ms/op
                 existUser·p0.50:   1.825 ms/op
                 existUser·p0.90:   2.511 ms/op
                 existUser·p0.95:   2.736 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  12.951 ms/op
                 existUser·p0.9999: 13.163 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16525
  mean =      1.952 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 847 
    [ 1.250,  2.500) = 13956 
    [ 2.500,  3.750) = 1486 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 109 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.281 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.511 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =     12.951 ms/op
     p(99.9900) =     13.163 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.234 ±(99.9%) 0.075 ms/op
Iteration   1: 1.859 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   1.718 ms/op
                 getUser·p0.90:   2.306 ms/op
                 getUser·p0.95:   2.611 ms/op
                 getUser·p0.99:   4.195 ms/op
                 getUser·p0.999:  13.400 ms/op
                 getUser·p0.9999: 14.090 ms/op
                 getUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17189
  mean =      1.859 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 15929 
    [ 2.500,  3.750) = 949 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.611 ms/op
     p(99.0000) =      4.195 ms/op
     p(99.9000) =     13.400 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


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
# Warmup Iteration   1: 4.915 ±(99.9%) 0.136 ms/op
Iteration   1: 3.519 ±(99.9%) 0.066 ms/op
                 listUser·p0.00:   0.567 ms/op
                 listUser·p0.50:   3.363 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  24.604 ms/op
                 listUser·p0.9999: 43.778 ms/op
                 listUser·p1.00:   43.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9067
  mean =      3.519 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8677 
    [ 5.000, 10.000) = 324 
    [10.000, 15.000) = 1 
    [15.000, 20.000) = 33 
    [20.000, 25.000) = 24 
    [25.000, 30.000) = 5 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     24.604 ms/op
     p(99.9900) =     43.778 ms/op
     p(99.9990) =     43.778 ms/op
     p(99.9999) =     43.778 ms/op
    p(100.0000) =     43.778 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.460          ops/ms
ClientSimple.existUser                       thrpt         12.491          ops/ms
ClientSimple.getUser                         thrpt         15.432          ops/ms
ClientSimple.listUser                        thrpt          8.336          ops/ms
ClientSimple.createUser                       avgt          2.247           ms/op
ClientSimple.existUser                        avgt          1.723           ms/op
ClientSimple.getUser                          avgt          2.019           ms/op
ClientSimple.listUser                         avgt          3.251           ms/op
ClientSimple.createUser                     sample  13718   2.331 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.604           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.077           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.769           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.930           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.690           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.042           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.164           ms/op
ClientSimple.existUser                      sample  16525   1.952 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.281           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.825           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.511           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.736           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.038           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.951           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.163           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.206           ms/op
ClientSimple.getUser                        sample  17189   1.859 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.725           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.718           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.306           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.611           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.195           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.400           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.090           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.172           ms/op
ClientSimple.listUser                       sample   9067   3.519 ± 0.066   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.567           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.363           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.241           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.604           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         43.778           ms/op
ClientSimple.listUser:listUser·p1.00        sample         43.778           ms/op

Benchmark result is saved to 1714006281173.json
