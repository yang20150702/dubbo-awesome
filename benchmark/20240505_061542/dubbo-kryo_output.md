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
# Warmup Iteration   1: 1.369 ops/ms
Iteration   1: 6.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.566 ops/ms


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
# Warmup Iteration   1: 6.359 ops/ms
Iteration   1: 11.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.996 ops/ms


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
# Warmup Iteration   1: 5.580 ops/ms
Iteration   1: 12.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.547 ops/ms


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
# Warmup Iteration   1: 4.650 ops/ms
Iteration   1: 8.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.510 ops/ms


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.064 ms/op
Iteration   1: 2.108 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.108 ms/op


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
# Warmup Iteration   1: 3.464 ±(99.9%) 0.060 ms/op
Iteration   1: 2.076 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.076 ms/op


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
# Warmup Iteration   1: 3.397 ±(99.9%) 0.058 ms/op
Iteration   1: 1.956 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.956 ms/op


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.082 ms/op
Iteration   1: 3.498 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.498 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.089 ms/op
Iteration   1: 2.445 ±(99.9%) 0.062 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   2.261 ms/op
                 createUser·p0.90:   2.818 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   7.455 ms/op
                 createUser·p0.999:  40.759 ms/op
                 createUser·p0.9999: 43.319 ms/op
                 createUser·p1.00:   43.319 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13067
  mean =      2.445 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12874 
    [ 5.000, 10.000) = 97 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.261 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     40.759 ms/op
     p(99.9900) =     43.319 ms/op
     p(99.9990) =     43.319 ms/op
     p(99.9999) =     43.319 ms/op
    p(100.0000) =     43.319 ms/op


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
# Warmup Iteration   1: 3.162 ±(99.9%) 0.081 ms/op
Iteration   1: 1.925 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   1.823 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   4.014 ms/op
                 existUser·p0.999:  12.838 ms/op
                 existUser·p0.9999: 13.479 ms/op
                 existUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16612
  mean =      1.925 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 15745 
    [ 2.500,  3.750) = 507 
    [ 3.750,  5.000) = 132 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =     12.838 ms/op
     p(99.9900) =     13.479 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


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
# Warmup Iteration   1: 3.493 ±(99.9%) 0.102 ms/op
Iteration   1: 1.915 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   1.812 ms/op
                 getUser·p0.90:   2.413 ms/op
                 getUser·p0.95:   2.597 ms/op
                 getUser·p0.99:   3.334 ms/op
                 getUser·p0.999:  13.599 ms/op
                 getUser·p0.9999: 13.697 ms/op
                 getUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16718
  mean =      1.915 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 231 
    [ 1.250,  2.500) = 15249 
    [ 2.500,  3.750) = 1091 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.334 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     13.697 ms/op
     p(99.9990) =     13.697 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.153 ms/op
Iteration   1: 3.586 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.099 ms/op
                 listUser·p0.999:  14.094 ms/op
                 listUser·p0.9999: 14.172 ms/op
                 listUser·p1.00:   14.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8921
  mean =      3.586 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 785 
    [ 2.500,  3.750) = 4952 
    [ 3.750,  5.000) = 2784 
    [ 5.000,  6.250) = 231 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.099 ms/op
     p(99.9000) =     14.094 ms/op
     p(99.9900) =     14.172 ms/op
     p(99.9990) =     14.172 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.566          ops/ms
ClientSimple.existUser                       thrpt         11.996          ops/ms
ClientSimple.getUser                         thrpt         12.547          ops/ms
ClientSimple.listUser                        thrpt          8.510          ops/ms
ClientSimple.createUser                       avgt          2.108           ms/op
ClientSimple.existUser                        avgt          2.076           ms/op
ClientSimple.getUser                          avgt          1.956           ms/op
ClientSimple.listUser                         avgt          3.498           ms/op
ClientSimple.createUser                     sample  13067   2.445 ± 0.062   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.685           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.261           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.146           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.455           ms/op
ClientSimple.createUser:createUser·p0.999   sample         40.759           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         43.319           ms/op
ClientSimple.createUser:createUser·p1.00    sample         43.319           ms/op
ClientSimple.existUser                      sample  16612   1.925 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.937           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.823           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.454           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.014           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.838           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.479           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.566           ms/op
ClientSimple.getUser                        sample  16718   1.915 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.751           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.812           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.334           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.599           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.697           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.697           ms/op
ClientSimple.listUser                       sample   8921   3.586 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.899           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.535           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.099           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.094           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.172           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.172           ms/op

Benchmark result is saved to 1714889465617.json
