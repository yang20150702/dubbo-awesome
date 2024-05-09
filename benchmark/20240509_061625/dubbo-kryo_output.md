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
# Warmup Iteration   1: 1.823 ops/ms
Iteration   1: 7.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.108 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.327 ops/ms
Iteration   1: 12.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.450 ops/ms


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
# Warmup Iteration   1: 5.014 ops/ms
Iteration   1: 12.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.490 ops/ms


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
# Warmup Iteration   1: 5.399 ops/ms
Iteration   1: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.104 ops/ms


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
# Warmup Iteration   1: 4.379 ±(99.9%) 0.079 ms/op
Iteration   1: 2.138 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.138 ms/op


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
# Warmup Iteration   1: 3.180 ±(99.9%) 0.059 ms/op
Iteration   1: 1.957 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.957 ms/op


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
# Warmup Iteration   1: 3.160 ±(99.9%) 0.056 ms/op
Iteration   1: 2.181 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.181 ms/op


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
# Warmup Iteration   1: 4.589 ±(99.9%) 0.089 ms/op
Iteration   1: 3.574 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.574 ms/op


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.092 ms/op
Iteration   1: 1.938 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   1.823 ms/op
                 createUser·p0.90:   2.454 ms/op
                 createUser·p0.95:   2.638 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  13.599 ms/op
                 createUser·p0.9999: 14.844 ms/op
                 createUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16492
  mean =      1.938 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1260 
    [ 1.250,  2.500) = 13804 
    [ 2.500,  3.750) = 1150 
    [ 3.750,  5.000) = 126 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.454 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     14.844 ms/op
     p(99.9990) =     14.844 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 2.955 ±(99.9%) 0.072 ms/op
Iteration   1: 2.058 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.263 ms/op
                 existUser·p0.50:   1.851 ms/op
                 existUser·p0.90:   2.617 ms/op
                 existUser·p0.95:   2.871 ms/op
                 existUser·p0.99:   4.633 ms/op
                 existUser·p0.999:  30.540 ms/op
                 existUser·p0.9999: 31.327 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15540
  mean =      2.058 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13254 
    [ 2.500,  5.000) = 2153 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.263 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.871 ms/op
     p(99.0000) =      4.633 ms/op
     p(99.9000) =     30.540 ms/op
     p(99.9900) =     31.327 ms/op
     p(99.9990) =     31.654 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 3.273 ±(99.9%) 0.078 ms/op
Iteration   1: 1.890 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   1.812 ms/op
                 getUser·p0.90:   2.171 ms/op
                 getUser·p0.95:   2.417 ms/op
                 getUser·p0.99:   3.017 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 12.260 ms/op
                 getUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16950
  mean =      1.890 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 16299 
    [ 2.500,  3.750) = 479 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.171 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.017 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     12.260 ms/op
     p(99.9990) =     12.272 ms/op
     p(99.9999) =     12.272 ms/op
    p(100.0000) =     12.272 ms/op


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
# Warmup Iteration   1: 4.527 ±(99.9%) 0.153 ms/op
Iteration   1: 3.193 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.195 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   5.832 ms/op
                 listUser·p0.999:  6.783 ms/op
                 listUser·p0.9999: 7.282 ms/op
                 listUser·p1.00:   7.283 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10007
  mean =      3.193 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 795 
    [2.000, 2.500) = 1838 
    [2.500, 3.000) = 1784 
    [3.000, 3.500) = 1787 
    [3.500, 4.000) = 2089 
    [4.000, 4.500) = 933 
    [4.500, 5.000) = 470 
    [5.000, 5.500) = 158 
    [5.500, 6.000) = 80 
    [6.000, 6.500) = 24 
    [6.500, 7.000) = 43 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      5.832 ms/op
     p(99.9000) =      6.783 ms/op
     p(99.9900) =      7.282 ms/op
     p(99.9990) =      7.283 ms/op
     p(99.9999) =      7.283 ms/op
    p(100.0000) =      7.283 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.108          ops/ms
ClientSimple.existUser                       thrpt         12.450          ops/ms
ClientSimple.getUser                         thrpt         12.490          ops/ms
ClientSimple.listUser                        thrpt          8.104          ops/ms
ClientSimple.createUser                       avgt          2.138           ms/op
ClientSimple.existUser                        avgt          1.957           ms/op
ClientSimple.getUser                          avgt          2.181           ms/op
ClientSimple.listUser                         avgt          3.574           ms/op
ClientSimple.createUser                     sample  16492   1.938 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.565           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.823           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.454           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.653           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.599           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.844           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.844           ms/op
ClientSimple.existUser                      sample  15540   2.058 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.263           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.851           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.871           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.633           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.540           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.327           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.654           ms/op
ClientSimple.getUser                        sample  16950   1.890 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.709           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.812           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.171           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.017           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.206           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.260           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.272           ms/op
ClientSimple.listUser                       sample  10007   3.193 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.466           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.195           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.832           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.783           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.282           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.283           ms/op

Benchmark result is saved to 1715235128462.json
