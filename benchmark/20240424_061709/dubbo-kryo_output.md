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
# Warmup Iteration   1: 1.947 ops/ms
Iteration   1: 5.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.541 ops/ms


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
# Warmup Iteration   1: 6.857 ops/ms
Iteration   1: 14.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.393 ops/ms


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
# Warmup Iteration   1: 6.450 ops/ms
Iteration   1: 12.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.607 ops/ms


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
# Warmup Iteration   1: 4.953 ops/ms
Iteration   1: 8.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.576 ops/ms


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
# Warmup Iteration   1: 3.846 ±(99.9%) 0.082 ms/op
Iteration   1: 2.244 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.244 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.057 ms/op
Iteration   1: 2.100 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.100 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.061 ms/op
Iteration   1: 2.256 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.256 ms/op


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.085 ms/op
Iteration   1: 3.560 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.560 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.092 ms/op
Iteration   1: 2.181 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   2.064 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   2.798 ms/op
                 createUser·p0.99:   5.566 ms/op
                 createUser·p0.999:  18.547 ms/op
                 createUser·p0.9999: 19.993 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14651
  mean =      2.181 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12460 
    [ 2.500,  5.000) = 2008 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      5.566 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     19.993 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 2.956 ±(99.9%) 0.076 ms/op
Iteration   1: 1.803 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.557 ms/op
                 existUser·p0.50:   1.675 ms/op
                 existUser·p0.90:   2.058 ms/op
                 existUser·p0.95:   2.232 ms/op
                 existUser·p0.99:   3.351 ms/op
                 existUser·p0.999:  29.761 ms/op
                 existUser·p0.9999: 30.711 ms/op
                 existUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17778
  mean =      1.803 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17355 
    [ 2.500,  5.000) = 345 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.058 ms/op
     p(95.0000) =      2.232 ms/op
     p(99.0000) =      3.351 ms/op
     p(99.9000) =     29.761 ms/op
     p(99.9900) =     30.711 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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
# Warmup Iteration   1: 3.504 ±(99.9%) 0.095 ms/op
Iteration   1: 2.182 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   2.146 ms/op
                 getUser·p0.90:   2.666 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   3.664 ms/op
                 getUser·p0.999:  10.488 ms/op
                 getUser·p0.9999: 11.233 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14922
  mean =      2.182 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 12145 
    [ 2.500,  3.750) = 2505 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.146 ms/op
     p(90.0000) =      2.666 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.664 ms/op
     p(99.9000) =     10.488 ms/op
     p(99.9900) =     11.233 ms/op
     p(99.9990) =     11.354 ms/op
     p(99.9999) =     11.354 ms/op
    p(100.0000) =     11.354 ms/op


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.114 ms/op
Iteration   1: 3.601 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   6.507 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 18.612 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8933
  mean =      3.601 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 757 
    [ 2.500,  3.750) = 4547 
    [ 3.750,  5.000) = 3187 
    [ 5.000,  6.250) = 332 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.989 ms/op
     p(99.0000) =      6.507 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     18.612 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.541          ops/ms
ClientSimple.existUser                       thrpt         14.393          ops/ms
ClientSimple.getUser                         thrpt         12.607          ops/ms
ClientSimple.listUser                        thrpt          8.576          ops/ms
ClientSimple.createUser                       avgt          2.244           ms/op
ClientSimple.existUser                        avgt          2.100           ms/op
ClientSimple.getUser                          avgt          2.256           ms/op
ClientSimple.listUser                         avgt          3.560           ms/op
ClientSimple.createUser                     sample  14651   2.181 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.736           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.064           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.566           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.547           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.993           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.054           ms/op
ClientSimple.existUser                      sample  17778   1.803 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.557           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.675           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.058           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.351           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.761           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.711           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.736           ms/op
ClientSimple.getUser                        sample  14922   2.182 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.684           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.146           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.664           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.488           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.233           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.354           ms/op
ClientSimple.listUser                       sample   8933   3.601 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.233           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.989           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.507           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.579           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.612           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.612           ms/op

Benchmark result is saved to 1713939166879.json
