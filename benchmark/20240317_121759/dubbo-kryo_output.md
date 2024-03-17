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
# Warmup Iteration   1: 1.946 ops/ms
Iteration   1: 6.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.690 ops/ms


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
# Warmup Iteration   1: 6.529 ops/ms
Iteration   1: 11.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.869 ops/ms


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
# Warmup Iteration   1: 6.088 ops/ms
Iteration   1: 14.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.868 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.626 ops/ms
Iteration   1: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.683 ops/ms


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.071 ms/op
Iteration   1: 2.221 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.221 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.069 ms/op
Iteration   1: 1.892 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.892 ms/op


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
# Warmup Iteration   1: 3.404 ±(99.9%) 0.073 ms/op
Iteration   1: 1.809 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.809 ms/op


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
# Warmup Iteration   1: 4.184 ±(99.9%) 0.086 ms/op
Iteration   1: 3.920 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.920 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.091 ms/op
Iteration   1: 2.124 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.603 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.421 ms/op
                 createUser·p0.95:   2.703 ms/op
                 createUser·p0.99:   8.219 ms/op
                 createUser·p0.999:  15.340 ms/op
                 createUser·p0.9999: 17.924 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15073
  mean =      2.124 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 13746 
    [ 2.500,  3.750) = 798 
    [ 3.750,  5.000) = 100 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      8.219 ms/op
     p(99.9000) =     15.340 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 3.108 ±(99.9%) 0.088 ms/op
Iteration   1: 1.958 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   1.919 ms/op
                 existUser·p0.90:   2.298 ms/op
                 existUser·p0.95:   2.437 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  12.485 ms/op
                 existUser·p0.9999: 12.933 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16334
  mean =      1.958 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 296 
    [ 1.250,  2.500) = 15405 
    [ 2.500,  3.750) = 479 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.298 ms/op
     p(95.0000) =      2.437 ms/op
     p(99.0000) =      3.391 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     12.933 ms/op
     p(99.9990) =     12.943 ms/op
     p(99.9999) =     12.943 ms/op
    p(100.0000) =     12.943 ms/op


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
# Warmup Iteration   1: 3.132 ±(99.9%) 0.077 ms/op
Iteration   1: 1.928 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   1.778 ms/op
                 getUser·p0.90:   2.265 ms/op
                 getUser·p0.95:   2.470 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  25.598 ms/op
                 getUser·p0.9999: 27.230 ms/op
                 getUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16703
  mean =      1.928 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15925 
    [ 2.500,  5.000) = 632 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =     25.598 ms/op
     p(99.9900) =     27.230 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 4.808 ±(99.9%) 0.132 ms/op
Iteration   1: 3.427 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.478 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.349 ms/op
                 listUser·p0.999:  6.379 ms/op
                 listUser·p0.9999: 8.184 ms/op
                 listUser·p1.00:   8.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9325
  mean =      3.427 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 150 
    [2.000, 2.500) = 793 
    [2.500, 3.000) = 1575 
    [3.000, 3.500) = 2270 
    [3.500, 4.000) = 2792 
    [4.000, 4.500) = 1321 
    [4.500, 5.000) = 276 
    [5.000, 5.500) = 55 
    [5.500, 6.000) = 39 
    [6.000, 6.500) = 27 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 5 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      6.379 ms/op
     p(99.9900) =      8.184 ms/op
     p(99.9990) =      8.184 ms/op
     p(99.9999) =      8.184 ms/op
    p(100.0000) =      8.184 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.690          ops/ms
ClientSimple.existUser                       thrpt         11.869          ops/ms
ClientSimple.getUser                         thrpt         14.868          ops/ms
ClientSimple.listUser                        thrpt          8.683          ops/ms
ClientSimple.createUser                       avgt          2.221           ms/op
ClientSimple.existUser                        avgt          1.892           ms/op
ClientSimple.getUser                          avgt          1.809           ms/op
ClientSimple.listUser                         avgt          3.920           ms/op
ClientSimple.createUser                     sample  15073   2.124 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.603           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.421           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.219           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.340           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.924           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.924           ms/op
ClientSimple.existUser                      sample  16334   1.958 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.634           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.391           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.485           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.933           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.943           ms/op
ClientSimple.getUser                        sample  16703   1.928 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.675           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.778           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.265           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.399           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.598           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.230           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.296           ms/op
ClientSimple.listUser                       sample   9325   3.427 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.046           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.478           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.349           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.379           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.184           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.184           ms/op

Benchmark result is saved to 1710677623102.json
