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
# Warmup Iteration   1: 2.075 ops/ms
Iteration   1: 7.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.618 ops/ms


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
# Warmup Iteration   1: 6.921 ops/ms
Iteration   1: 12.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.448 ops/ms


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
# Warmup Iteration   1: 5.801 ops/ms
Iteration   1: 11.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.904 ops/ms


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
# Warmup Iteration   1: 4.663 ops/ms
Iteration   1: 7.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.961 ops/ms


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.071 ms/op
Iteration   1: 2.187 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.187 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.052 ms/op
Iteration   1: 1.958 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.958 ms/op


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
# Warmup Iteration   1: 3.280 ±(99.9%) 0.056 ms/op
Iteration   1: 1.992 ±(99.9%) 0.006 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.003 ±(99.9%) 0.098 ms/op
Iteration   1: 3.101 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.101 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.092 ms/op
Iteration   1: 2.424 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.626 ms/op
                 createUser·p0.50:   2.376 ms/op
                 createUser·p0.90:   2.916 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.935 ms/op
                 createUser·p0.999:  18.074 ms/op
                 createUser·p0.9999: 19.229 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13433
  mean =      2.424 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 8879 
    [ 2.500,  3.750) = 4349 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      2.376 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.935 ms/op
     p(99.9000) =     18.074 ms/op
     p(99.9900) =     19.229 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.273 ±(99.9%) 0.088 ms/op
Iteration   1: 1.816 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   1.737 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.359 ms/op
                 existUser·p0.99:   3.075 ms/op
                 existUser·p0.999:  10.443 ms/op
                 existUser·p0.9999: 10.604 ms/op
                 existUser·p1.00:   10.666 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17620
  mean =      1.816 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 11 
    [ 1.000,  2.000) = 14918 
    [ 2.000,  3.000) = 2487 
    [ 3.000,  4.000) = 90 
    [ 4.000,  5.000) = 39 
    [ 5.000,  6.000) = 3 
    [ 6.000,  7.000) = 7 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      1.737 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.359 ms/op
     p(99.0000) =      3.075 ms/op
     p(99.9000) =     10.443 ms/op
     p(99.9900) =     10.604 ms/op
     p(99.9990) =     10.666 ms/op
     p(99.9999) =     10.666 ms/op
    p(100.0000) =     10.666 ms/op


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
# Warmup Iteration   1: 3.164 ±(99.9%) 0.088 ms/op
Iteration   1: 2.011 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   1.915 ms/op
                 getUser·p0.90:   2.454 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  17.990 ms/op
                 getUser·p0.9999: 18.371 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15901
  mean =      2.011 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 327 
    [ 1.250,  2.500) = 14215 
    [ 2.500,  3.750) = 1098 
    [ 3.750,  5.000) = 152 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     18.371 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.117 ms/op
Iteration   1: 3.648 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  17.768 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8774
  mean =      3.648 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 297 
    [ 2.500,  3.750) = 5487 
    [ 3.750,  5.000) = 2640 
    [ 5.000,  6.250) = 188 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     17.768 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.618          ops/ms
ClientSimple.existUser                       thrpt         12.448          ops/ms
ClientSimple.getUser                         thrpt         11.904          ops/ms
ClientSimple.listUser                        thrpt          7.961          ops/ms
ClientSimple.createUser                       avgt          2.187           ms/op
ClientSimple.existUser                        avgt          1.958           ms/op
ClientSimple.getUser                          avgt          1.992           ms/op
ClientSimple.listUser                         avgt          3.101           ms/op
ClientSimple.createUser                     sample  13433   2.424 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.626           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.376           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.105           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.935           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.074           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.229           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.792           ms/op
ClientSimple.existUser                      sample  17620   1.816 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.754           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.737           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.138           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.075           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.443           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.604           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.666           ms/op
ClientSimple.getUser                        sample  15901   2.011 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.768           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.915           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.454           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.620           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.990           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.371           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.448           ms/op
ClientSimple.listUser                       sample   8774   3.648 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.219           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.559           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.996           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.768           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.055           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.055           ms/op

Benchmark result is saved to 1716747051883.json
