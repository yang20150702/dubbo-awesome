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
# Warmup Iteration   1: 1.814 ops/ms
Iteration   1: 7.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.462 ops/ms


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
# Warmup Iteration   1: 5.973 ops/ms
Iteration   1: 12.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.870 ops/ms


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
# Warmup Iteration   1: 5.638 ops/ms
Iteration   1: 12.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.299 ops/ms


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
# Warmup Iteration   1: 5.226 ops/ms
Iteration   1: 8.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.859 ops/ms


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.090 ms/op
Iteration   1: 2.223 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.223 ms/op


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
# Warmup Iteration   1: 3.071 ±(99.9%) 0.058 ms/op
Iteration   1: 1.878 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.878 ms/op


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
# Warmup Iteration   1: 3.344 ±(99.9%) 0.057 ms/op
Iteration   1: 2.015 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.015 ms/op


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.098 ms/op
Iteration   1: 3.493 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.493 ms/op


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.086 ms/op
Iteration   1: 2.224 ±(99.9%) 0.073 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   1.860 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   8.952 ms/op
                 createUser·p0.999:  43.057 ms/op
                 createUser·p0.9999: 55.253 ms/op
                 createUser·p1.00:   55.575 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14463
  mean =      2.224 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14166 
    [ 5.000, 10.000) = 161 
    [10.000, 15.000) = 65 
    [15.000, 20.000) = 7 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 28 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      8.952 ms/op
     p(99.9000) =     43.057 ms/op
     p(99.9900) =     55.253 ms/op
     p(99.9990) =     55.575 ms/op
     p(99.9999) =     55.575 ms/op
    p(100.0000) =     55.575 ms/op


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
# Warmup Iteration   1: 3.015 ±(99.9%) 0.065 ms/op
Iteration   1: 1.957 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.298 ms/op
                 existUser·p0.50:   1.845 ms/op
                 existUser·p0.90:   2.458 ms/op
                 existUser·p0.95:   2.666 ms/op
                 existUser·p0.99:   3.169 ms/op
                 existUser·p0.999:  10.551 ms/op
                 existUser·p0.9999: 16.331 ms/op
                 existUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16279
  mean =      1.957 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 540 
    [ 1.250,  2.500) = 14326 
    [ 2.500,  3.750) = 1306 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.458 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      3.169 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     16.331 ms/op
     p(99.9990) =     16.351 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


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
# Warmup Iteration   1: 3.295 ±(99.9%) 0.089 ms/op
Iteration   1: 2.153 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   2.056 ms/op
                 getUser·p0.90:   2.728 ms/op
                 getUser·p0.95:   3.004 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  13.634 ms/op
                 getUser·p0.9999: 14.018 ms/op
                 getUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14849
  mean =      2.153 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 92 
    [ 1.250,  2.500) = 12274 
    [ 2.500,  3.750) = 2253 
    [ 3.750,  5.000) = 137 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      3.004 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     13.634 ms/op
     p(99.9900) =     14.018 ms/op
     p(99.9990) =     14.074 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 4.594 ±(99.9%) 0.127 ms/op
Iteration   1: 3.387 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.355 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.268 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 17.072 ms/op
                 listUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9446
  mean =      3.387 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 906 
    [ 2.500,  3.750) = 5751 
    [ 3.750,  5.000) = 2620 
    [ 5.000,  6.250) = 135 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.268 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     17.072 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.462          ops/ms
ClientSimple.existUser                       thrpt         12.870          ops/ms
ClientSimple.getUser                         thrpt         12.299          ops/ms
ClientSimple.listUser                        thrpt          8.859          ops/ms
ClientSimple.createUser                       avgt          2.223           ms/op
ClientSimple.existUser                        avgt          1.878           ms/op
ClientSimple.getUser                          avgt          2.015           ms/op
ClientSimple.listUser                         avgt          3.493           ms/op
ClientSimple.createUser                     sample  14463   2.224 ± 0.073   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.508           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.860           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.952           ms/op
ClientSimple.createUser:createUser·p0.999   sample         43.057           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         55.253           ms/op
ClientSimple.createUser:createUser·p1.00    sample         55.575           ms/op
ClientSimple.existUser                      sample  16279   1.957 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.298           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.845           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.666           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.169           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.551           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.331           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.351           ms/op
ClientSimple.getUser                        sample  14849   2.153 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.695           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.056           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.004           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.604           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.634           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.018           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.074           ms/op
ClientSimple.listUser                       sample   9446   3.387 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.341           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.355           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.268           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.039           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.072           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.072           ms/op

Benchmark result is saved to 1714091883650.json
