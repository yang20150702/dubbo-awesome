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
# Warmup Iteration   1: 1.695 ops/ms
Iteration   1: 6.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.675 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.012 ops/ms
Iteration   1: 15.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  15.000 ops/ms


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
# Warmup Iteration   1: 6.377 ops/ms
Iteration   1: 13.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.656 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.422 ops/ms
Iteration   1: 8.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.447 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.716 ±(99.9%) 0.061 ms/op
Iteration   1: 2.249 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.249 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.047 ms/op
Iteration   1: 1.730 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.730 ms/op


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
# Warmup Iteration   1: 3.228 ±(99.9%) 0.075 ms/op
Iteration   1: 1.992 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.992 ms/op


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
# Warmup Iteration   1: 4.386 ±(99.9%) 0.138 ms/op
Iteration   1: 3.441 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.441 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.076 ms/op
Iteration   1: 2.301 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   2.095 ms/op
                 createUser·p0.90:   2.826 ms/op
                 createUser·p0.95:   3.311 ms/op
                 createUser·p0.99:   9.503 ms/op
                 createUser·p0.999:  29.066 ms/op
                 createUser·p0.9999: 30.605 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13965
  mean =      2.301 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10998 
    [ 2.500,  5.000) = 2722 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.095 ms/op
     p(90.0000) =      2.826 ms/op
     p(95.0000) =      3.311 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     29.066 ms/op
     p(99.9900) =     30.605 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.155 ±(99.9%) 0.082 ms/op
Iteration   1: 1.735 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.406 ms/op
                 existUser·p0.50:   1.518 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  26.903 ms/op
                 existUser·p0.9999: 27.430 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18896
  mean =      1.735 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17488 
    [ 2.500,  5.000) = 1268 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      1.518 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =     26.903 ms/op
     p(99.9900) =     27.430 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.180 ±(99.9%) 0.078 ms/op
Iteration   1: 2.031 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.283 ms/op
                 getUser·p0.50:   1.921 ms/op
                 getUser·p0.90:   2.556 ms/op
                 getUser·p0.95:   2.671 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  12.173 ms/op
                 getUser·p0.9999: 12.859 ms/op
                 getUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15742
  mean =      2.031 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 249 
    [ 1.250,  2.500) = 13430 
    [ 2.500,  3.750) = 1886 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.283 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =     12.173 ms/op
     p(99.9900) =     12.859 ms/op
     p(99.9990) =     12.878 ms/op
     p(99.9999) =     12.878 ms/op
    p(100.0000) =     12.878 ms/op


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
# Warmup Iteration   1: 4.484 ±(99.9%) 0.127 ms/op
Iteration   1: 3.458 ±(99.9%) 0.065 ms/op
                 listUser·p0.00:   0.804 ms/op
                 listUser·p0.50:   3.293 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.784 ms/op
                 listUser·p0.999:  32.735 ms/op
                 listUser·p0.9999: 34.734 ms/op
                 listUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9245
  mean =      3.458 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 940 
    [ 2.500,  5.000) = 8027 
    [ 5.000,  7.500) = 211 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.784 ms/op
     p(99.9000) =     32.735 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.675          ops/ms
ClientSimple.existUser                       thrpt         15.000          ops/ms
ClientSimple.getUser                         thrpt         13.656          ops/ms
ClientSimple.listUser                        thrpt          8.447          ops/ms
ClientSimple.createUser                       avgt          2.249           ms/op
ClientSimple.existUser                        avgt          1.730           ms/op
ClientSimple.getUser                          avgt          1.992           ms/op
ClientSimple.listUser                         avgt          3.441           ms/op
ClientSimple.createUser                     sample  13965   2.301 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.585           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.095           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.311           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.503           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.066           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.605           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.605           ms/op
ClientSimple.existUser                      sample  18896   1.735 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.406           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.518           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.284           ms/op
ClientSimple.existUser:existUser·p0.999     sample         26.903           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.430           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.460           ms/op
ClientSimple.getUser                        sample  15742   2.031 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.283           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.921           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.671           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.219           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.173           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.859           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.878           ms/op
ClientSimple.listUser                       sample   9245   3.458 ± 0.065   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.804           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.293           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.784           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.735           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         34.734           ms/op
ClientSimple.listUser:listUser·p1.00        sample         34.734           ms/op

Benchmark result is saved to 1714284649453.json
