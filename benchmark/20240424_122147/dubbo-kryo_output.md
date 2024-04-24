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
# Warmup Iteration   1: 1.661 ops/ms
Iteration   1: 6.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.484 ops/ms


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
# Warmup Iteration   1: 6.699 ops/ms
Iteration   1: 12.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.014 ops/ms


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
# Warmup Iteration   1: 6.356 ops/ms
Iteration   1: 13.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.969 ops/ms


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
# Warmup Iteration   1: 4.670 ops/ms
Iteration   1: 8.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.282 ops/ms


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.052 ms/op
Iteration   1: 2.184 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.184 ms/op


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
# Warmup Iteration   1: 3.476 ±(99.9%) 0.056 ms/op
Iteration   1: 1.896 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.896 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.055 ms/op
Iteration   1: 2.016 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.016 ms/op


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.096 ms/op
Iteration   1: 3.514 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.514 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.082 ms/op
Iteration   1: 2.255 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   2.054 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   8.348 ms/op
                 createUser·p0.999:  16.679 ms/op
                 createUser·p0.9999: 19.319 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14176
  mean =      2.255 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 12111 
    [ 2.500,  3.750) = 1491 
    [ 3.750,  5.000) = 150 
    [ 5.000,  6.250) = 101 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     19.319 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 3.094 ±(99.9%) 0.084 ms/op
Iteration   1: 1.822 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.237 ms/op
                 existUser·p0.50:   1.692 ms/op
                 existUser·p0.90:   2.343 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.380 ms/op
                 existUser·p0.999:  13.049 ms/op
                 existUser·p0.9999: 14.036 ms/op
                 existUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17542
  mean =      1.822 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 672 
    [ 1.250,  2.500) = 16031 
    [ 2.500,  3.750) = 742 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.237 ms/op
     p(50.0000) =      1.692 ms/op
     p(90.0000) =      2.343 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.380 ms/op
     p(99.9000) =     13.049 ms/op
     p(99.9900) =     14.036 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.092 ms/op
Iteration   1: 1.912 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   1.831 ms/op
                 getUser·p0.90:   2.339 ms/op
                 getUser·p0.95:   2.503 ms/op
                 getUser·p0.99:   3.588 ms/op
                 getUser·p0.999:  19.890 ms/op
                 getUser·p0.9999: 21.254 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16836
  mean =      1.912 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15988 
    [ 2.500,  5.000) = 778 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     21.254 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 4.530 ±(99.9%) 0.135 ms/op
Iteration   1: 3.260 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.252 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.021 ms/op
                 listUser·p0.999:  12.274 ms/op
                 listUser·p0.9999: 14.582 ms/op
                 listUser·p1.00:   14.582 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9895
  mean =      3.260 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1376 
    [ 2.500,  3.750) = 6405 
    [ 3.750,  5.000) = 1830 
    [ 5.000,  6.250) = 191 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.956 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     12.274 ms/op
     p(99.9900) =     14.582 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     14.582 ms/op
    p(100.0000) =     14.582 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.484          ops/ms
ClientSimple.existUser                       thrpt         12.014          ops/ms
ClientSimple.getUser                         thrpt         13.969          ops/ms
ClientSimple.listUser                        thrpt          8.282          ops/ms
ClientSimple.createUser                       avgt          2.184           ms/op
ClientSimple.existUser                        avgt          1.896           ms/op
ClientSimple.getUser                          avgt          2.016           ms/op
ClientSimple.listUser                         avgt          3.514           ms/op
ClientSimple.createUser                     sample  14176   2.255 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.824           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.054           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.052           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.348           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.679           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.319           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.333           ms/op
ClientSimple.existUser                      sample  17542   1.822 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.237           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.692           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.343           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.380           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.049           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.036           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.270           ms/op
ClientSimple.getUser                        sample  16836   1.912 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.724           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.831           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.339           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.588           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.890           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.254           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.299           ms/op
ClientSimple.listUser                       sample   9895   3.260 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.956           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.252           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.108           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.021           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.274           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.582           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.582           ms/op

Benchmark result is saved to 1713961051142.json
