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
# Warmup Iteration   1: 1.497 ops/ms
Iteration   1: 6.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.596 ops/ms


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
# Warmup Iteration   1: 5.683 ops/ms
Iteration   1: 13.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.599 ops/ms


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
# Warmup Iteration   1: 5.917 ops/ms
Iteration   1: 12.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.615 ops/ms


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
# Warmup Iteration   1: 4.811 ops/ms
Iteration   1: 8.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.527 ops/ms


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
# Warmup Iteration   1: 3.725 ±(99.9%) 0.067 ms/op
Iteration   1: 2.393 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.393 ms/op


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
# Warmup Iteration   1: 3.152 ±(99.9%) 0.061 ms/op
Iteration   1: 1.933 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.933 ms/op


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
# Warmup Iteration   1: 3.582 ±(99.9%) 0.066 ms/op
Iteration   1: 2.021 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.021 ms/op


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
# Warmup Iteration   1: 4.184 ±(99.9%) 0.104 ms/op
Iteration   1: 3.423 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.423 ms/op


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
# Warmup Iteration   1: 3.561 ±(99.9%) 0.082 ms/op
Iteration   1: 2.087 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   1.872 ms/op
                 createUser·p0.90:   2.421 ms/op
                 createUser·p0.95:   2.634 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  36.635 ms/op
                 createUser·p0.9999: 37.679 ms/op
                 createUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15323
  mean =      2.087 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14120 
    [ 2.500,  5.000) = 1050 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      5.153 ms/op
     p(99.9000) =     36.635 ms/op
     p(99.9900) =     37.679 ms/op
     p(99.9990) =     37.749 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


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
# Warmup Iteration   1: 2.796 ±(99.9%) 0.064 ms/op
Iteration   1: 2.021 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   1.853 ms/op
                 existUser·p0.90:   2.454 ms/op
                 existUser·p0.95:   2.694 ms/op
                 existUser·p0.99:   4.784 ms/op
                 existUser·p0.999:  25.362 ms/op
                 existUser·p0.9999: 30.768 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15824
  mean =      2.021 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14409 
    [ 2.500,  5.000) = 1287 
    [ 5.000,  7.500) = 30 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.694 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     30.768 ms/op
     p(99.9990) =     33.554 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.102 ms/op
Iteration   1: 1.788 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   1.673 ms/op
                 getUser·p0.90:   2.216 ms/op
                 getUser·p0.95:   2.433 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  11.372 ms/op
                 getUser·p0.9999: 11.847 ms/op
                 getUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17899
  mean =      1.788 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 373 
    [ 1.250,  2.500) = 16858 
    [ 2.500,  3.750) = 451 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.433 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     11.372 ms/op
     p(99.9900) =     11.847 ms/op
     p(99.9990) =     11.977 ms/op
     p(99.9999) =     11.977 ms/op
    p(100.0000) =     11.977 ms/op


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.117 ms/op
Iteration   1: 3.787 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   5.905 ms/op
                 listUser·p0.999:  18.520 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8452
  mean =      3.787 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 232 
    [ 2.500,  3.750) = 3633 
    [ 3.750,  5.000) = 4222 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      5.905 ms/op
     p(99.9000) =     18.520 ms/op
     p(99.9900) =     19.333 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.596          ops/ms
ClientSimple.existUser                       thrpt         13.599          ops/ms
ClientSimple.getUser                         thrpt         12.615          ops/ms
ClientSimple.listUser                        thrpt          8.527          ops/ms
ClientSimple.createUser                       avgt          2.393           ms/op
ClientSimple.existUser                        avgt          1.933           ms/op
ClientSimple.getUser                          avgt          2.021           ms/op
ClientSimple.listUser                         avgt          3.423           ms/op
ClientSimple.createUser                     sample  15323   2.087 ± 0.056   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.644           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.872           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.421           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.634           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.153           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.635           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         37.679           ms/op
ClientSimple.createUser:createUser·p1.00    sample         37.749           ms/op
ClientSimple.existUser                      sample  15824   2.021 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.669           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.694           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.784           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.362           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.768           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.554           ms/op
ClientSimple.getUser                        sample  17899   1.788 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.757           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.673           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.216           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.433           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.375           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.372           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.847           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.977           ms/op
ClientSimple.listUser                       sample   8452   3.787 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.067           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.809           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.905           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.520           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.333           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.333           ms/op

Benchmark result is saved to 1720246326235.json
