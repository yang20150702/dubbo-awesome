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
# Warmup Iteration   1: 2.041 ops/ms
Iteration   1: 7.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.353 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.582 ops/ms
Iteration   1: 12.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.907 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.533 ops/ms
Iteration   1: 13.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.351 ops/ms


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
# Warmup Iteration   1: 4.684 ops/ms
Iteration   1: 8.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.443 ops/ms


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
# Warmup Iteration   1: 3.621 ±(99.9%) 0.058 ms/op
Iteration   1: 2.282 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.282 ms/op


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
# Warmup Iteration   1: 3.079 ±(99.9%) 0.055 ms/op
Iteration   1: 1.678 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.678 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.056 ms/op
Iteration   1: 2.127 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.127 ms/op


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
# Warmup Iteration   1: 4.977 ±(99.9%) 0.095 ms/op
Iteration   1: 3.387 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.387 ms/op


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.094 ms/op
Iteration   1: 1.972 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   1.757 ms/op
                 createUser·p0.90:   2.384 ms/op
                 createUser·p0.95:   2.662 ms/op
                 createUser·p0.99:   5.371 ms/op
                 createUser·p0.999:  14.942 ms/op
                 createUser·p0.9999: 15.782 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16218
  mean =      1.972 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 14929 
    [ 2.500,  3.750) = 884 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      5.371 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     15.782 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.340 ±(99.9%) 0.180 ms/op
Iteration   1: 1.967 ±(99.9%) 0.049 ms/op
                 existUser·p0.00:   0.477 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.605 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  39.026 ms/op
                 existUser·p0.9999: 39.518 ms/op
                 existUser·p1.00:   39.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16515
  mean =      1.967 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15442 
    [ 2.500,  5.000) = 857 
    [ 5.000,  7.500) = 152 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.605 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     39.026 ms/op
     p(99.9900) =     39.518 ms/op
     p(99.9990) =     39.518 ms/op
     p(99.9999) =     39.518 ms/op
    p(100.0000) =     39.518 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.098 ms/op
Iteration   1: 2.016 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.585 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.454 ms/op
                 getUser·p0.95:   2.654 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  10.894 ms/op
                 getUser·p0.9999: 11.288 ms/op
                 getUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16046
  mean =      2.016 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 337 
    [ 1.250,  2.500) = 14376 
    [ 2.500,  3.750) = 1156 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =     10.894 ms/op
     p(99.9900) =     11.288 ms/op
     p(99.9990) =     11.338 ms/op
     p(99.9999) =     11.338 ms/op
    p(100.0000) =     11.338 ms/op


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.125 ms/op
Iteration   1: 3.696 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.508 ms/op
                 listUser·p0.999:  8.461 ms/op
                 listUser·p0.9999: 10.617 ms/op
                 listUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8580
  mean =      3.696 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 138 
    [ 2.000,  3.000) = 965 
    [ 3.000,  4.000) = 5210 
    [ 4.000,  5.000) = 1938 
    [ 5.000,  6.000) = 181 
    [ 6.000,  7.000) = 110 
    [ 7.000,  8.000) = 9 
    [ 8.000,  9.000) = 27 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      6.508 ms/op
     p(99.9000) =      8.461 ms/op
     p(99.9900) =     10.617 ms/op
     p(99.9990) =     10.617 ms/op
     p(99.9999) =     10.617 ms/op
    p(100.0000) =     10.617 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.353          ops/ms
ClientSimple.existUser                       thrpt         12.907          ops/ms
ClientSimple.getUser                         thrpt         13.351          ops/ms
ClientSimple.listUser                        thrpt          8.443          ops/ms
ClientSimple.createUser                       avgt          2.282           ms/op
ClientSimple.existUser                        avgt          1.678           ms/op
ClientSimple.getUser                          avgt          2.127           ms/op
ClientSimple.listUser                         avgt          3.387           ms/op
ClientSimple.createUser                     sample  16218   1.972 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.689           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.757           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.384           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.371           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.942           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.782           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.302           ms/op
ClientSimple.existUser                      sample  16515   1.967 ± 0.049   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.477           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.784           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.605           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.906           ms/op
ClientSimple.existUser:existUser·p0.999     sample         39.026           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         39.518           ms/op
ClientSimple.existUser:existUser·p1.00      sample         39.518           ms/op
ClientSimple.getUser                        sample  16046   2.016 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.585           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.454           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.654           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.125           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.894           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.288           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.338           ms/op
ClientSimple.listUser                       sample   8580   3.696 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.886           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.678           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.702           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.508           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.461           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.617           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.617           ms/op

Benchmark result is saved to 1721196821193.json
