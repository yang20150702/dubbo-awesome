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
# Warmup Iteration   1: 2.070 ops/ms
Iteration   1: 7.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.399 ops/ms


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
# Warmup Iteration   1: 6.868 ops/ms
Iteration   1: 12.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.265 ops/ms


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
# Warmup Iteration   1: 6.038 ops/ms
Iteration   1: 10.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.937 ops/ms


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
# Warmup Iteration   1: 5.151 ops/ms
Iteration   1: 8.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.892 ops/ms


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.087 ms/op
Iteration   1: 2.127 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.502 ±(99.9%) 0.085 ms/op
Iteration   1: 2.208 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.208 ms/op


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
# Warmup Iteration   1: 3.393 ±(99.9%) 0.056 ms/op
Iteration   1: 2.264 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.264 ms/op


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
# Warmup Iteration   1: 4.334 ±(99.9%) 0.073 ms/op
Iteration   1: 3.949 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.949 ms/op


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
# Warmup Iteration   1: 3.564 ±(99.9%) 0.091 ms/op
Iteration   1: 2.363 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.485 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.750 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   11.207 ms/op
                 createUser·p0.999:  31.425 ms/op
                 createUser·p0.9999: 32.128 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13535
  mean =      2.363 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10614 
    [ 2.500,  5.000) = 2738 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.750 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     31.425 ms/op
     p(99.9900) =     32.128 ms/op
     p(99.9990) =     32.244 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 3.006 ±(99.9%) 0.073 ms/op
Iteration   1: 1.979 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.654 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   3.659 ms/op
                 existUser·p0.999:  12.826 ms/op
                 existUser·p0.9999: 13.468 ms/op
                 existUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16133
  mean =      1.979 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1329 
    [ 1.250,  2.500) = 12309 
    [ 2.500,  3.750) = 2340 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      3.659 ms/op
     p(99.9000) =     12.826 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     13.599 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


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
# Warmup Iteration   1: 3.477 ±(99.9%) 0.083 ms/op
Iteration   1: 2.107 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.497 ms/op
                 getUser·p0.50:   1.950 ms/op
                 getUser·p0.90:   2.806 ms/op
                 getUser·p0.95:   3.006 ms/op
                 getUser·p0.99:   3.815 ms/op
                 getUser·p0.999:  29.786 ms/op
                 getUser·p0.9999: 30.334 ms/op
                 getUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15483
  mean =      2.107 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12589 
    [ 2.500,  5.000) = 2793 
    [ 5.000,  7.500) = 36 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      3.815 ms/op
     p(99.9000) =     29.786 ms/op
     p(99.9900) =     30.334 ms/op
     p(99.9990) =     30.441 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 4.586 ±(99.9%) 0.130 ms/op
Iteration   1: 3.793 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.376 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   5.806 ms/op
                 listUser·p0.999:  9.774 ms/op
                 listUser·p0.9999: 9.912 ms/op
                 listUser·p1.00:   9.912 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8428
  mean =      3.793 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 1 
    [ 1.500,  2.000) = 29 
    [ 2.000,  2.500) = 1056 
    [ 2.500,  3.000) = 931 
    [ 3.000,  3.500) = 488 
    [ 3.500,  4.000) = 1906 
    [ 4.000,  4.500) = 2544 
    [ 4.500,  5.000) = 1099 
    [ 5.000,  5.500) = 264 
    [ 5.500,  6.000) = 37 
    [ 6.000,  6.500) = 29 
    [ 6.500,  7.000) = 7 
    [ 7.000,  7.500) = 4 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      5.806 ms/op
     p(99.9000) =      9.774 ms/op
     p(99.9900) =      9.912 ms/op
     p(99.9990) =      9.912 ms/op
     p(99.9999) =      9.912 ms/op
    p(100.0000) =      9.912 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.399          ops/ms
ClientSimple.existUser                       thrpt         12.265          ops/ms
ClientSimple.getUser                         thrpt         10.937          ops/ms
ClientSimple.listUser                        thrpt          8.892          ops/ms
ClientSimple.createUser                       avgt          2.127           ms/op
ClientSimple.existUser                        avgt          2.208           ms/op
ClientSimple.getUser                          avgt          2.264           ms/op
ClientSimple.listUser                         avgt          3.949           ms/op
ClientSimple.createUser                     sample  13535   2.363 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.485           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.750           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.207           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.425           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.128           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.244           ms/op
ClientSimple.existUser                      sample  16133   1.979 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.593           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.659           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.826           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.468           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.599           ms/op
ClientSimple.getUser                        sample  15483   2.107 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.497           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.950           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.006           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.815           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.786           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.334           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.441           ms/op
ClientSimple.listUser                       sample   8428   3.793 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.376           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.953           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.806           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.774           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.912           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.912           ms/op

Benchmark result is saved to 1718281013808.json
