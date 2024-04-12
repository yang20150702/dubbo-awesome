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
# Warmup Iteration   1: 0.911 ops/ms
Iteration   1: 6.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.289 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.531 ops/ms
Iteration   1: 11.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.333 ops/ms


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
# Warmup Iteration   1: 5.354 ops/ms
Iteration   1: 11.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.069 ops/ms


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
# Warmup Iteration   1: 5.137 ops/ms
Iteration   1: 9.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.346 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.581 ±(99.9%) 0.064 ms/op
Iteration   1: 2.045 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.045 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.105 ±(99.9%) 0.052 ms/op
Iteration   1: 1.898 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.898 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.105 ±(99.9%) 0.053 ms/op
Iteration   1: 2.125 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.125 ms/op


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
# Warmup Iteration   1: 4.476 ±(99.9%) 0.079 ms/op
Iteration   1: 3.214 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.214 ms/op


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
# Warmup Iteration   1: 3.596 ±(99.9%) 0.095 ms/op
Iteration   1: 2.053 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   1.792 ms/op
                 createUser·p0.90:   2.335 ms/op
                 createUser·p0.95:   2.646 ms/op
                 createUser·p0.99:   6.676 ms/op
                 createUser·p0.999:  36.335 ms/op
                 createUser·p0.9999: 37.746 ms/op
                 createUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15574
  mean =      2.053 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14525 
    [ 2.500,  5.000) = 776 
    [ 5.000,  7.500) = 145 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.646 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     36.335 ms/op
     p(99.9900) =     37.746 ms/op
     p(99.9990) =     38.404 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.871 ±(99.9%) 0.062 ms/op
Iteration   1: 1.775 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   3.005 ms/op
                 existUser·p0.999:  12.024 ms/op
                 existUser·p0.9999: 12.675 ms/op
                 existUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18010
  mean =      1.775 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 635 
    [ 1.250,  2.500) = 16597 
    [ 2.500,  3.750) = 669 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.005 ms/op
     p(99.9000) =     12.024 ms/op
     p(99.9900) =     12.675 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.126 ms/op
Iteration   1: 2.026 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   1.903 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.941 ms/op
                 getUser·p0.99:   3.814 ms/op
                 getUser·p0.999:  12.190 ms/op
                 getUser·p0.9999: 12.567 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15857
  mean =      2.026 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 308 
    [ 1.250,  2.500) = 12785 
    [ 2.500,  3.750) = 2603 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      1.903 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      3.814 ms/op
     p(99.9000) =     12.190 ms/op
     p(99.9900) =     12.567 ms/op
     p(99.9990) =     12.567 ms/op
     p(99.9999) =     12.567 ms/op
    p(100.0000) =     12.567 ms/op


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
# Warmup Iteration   1: 4.667 ±(99.9%) 0.131 ms/op
Iteration   1: 3.135 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.826 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  26.865 ms/op
                 listUser·p0.9999: 27.841 ms/op
                 listUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10231
  mean =      3.135 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1436 
    [ 2.500,  5.000) = 8654 
    [ 5.000,  7.500) = 105 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     26.865 ms/op
     p(99.9900) =     27.841 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.289          ops/ms
ClientSimple.existUser                       thrpt         11.333          ops/ms
ClientSimple.getUser                         thrpt         11.069          ops/ms
ClientSimple.listUser                        thrpt          9.346          ops/ms
ClientSimple.createUser                       avgt          2.045           ms/op
ClientSimple.existUser                        avgt          1.898           ms/op
ClientSimple.getUser                          avgt          2.125           ms/op
ClientSimple.listUser                         avgt          3.214           ms/op
ClientSimple.createUser                     sample  15574   2.053 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.546           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.792           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.335           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.646           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.676           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.335           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.746           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.404           ms/op
ClientSimple.existUser                      sample  18010   1.775 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.626           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.645           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.005           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.024           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.675           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.714           ms/op
ClientSimple.getUser                        sample  15857   2.026 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.590           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.903           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.814           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.190           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.567           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.567           ms/op
ClientSimple.listUser                       sample  10231   3.135 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.883           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.826           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.936           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.407           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.865           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.841           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.853           ms/op

Benchmark result is saved to 1712924101682.json
