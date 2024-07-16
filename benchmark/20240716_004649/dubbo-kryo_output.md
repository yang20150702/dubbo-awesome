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
# Warmup Iteration   1: 2.287 ops/ms
Iteration   1: 7.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.923 ops/ms


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
# Warmup Iteration   1: 6.191 ops/ms
Iteration   1: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.805 ops/ms


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
# Warmup Iteration   1: 4.927 ops/ms
Iteration   1: 11.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.660 ops/ms


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
# Warmup Iteration   1: 4.685 ops/ms
Iteration   1: 8.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.036 ops/ms


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.071 ms/op
Iteration   1: 2.301 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.301 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.055 ms/op
Iteration   1: 1.994 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.994 ms/op


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
# Warmup Iteration   1: 3.322 ±(99.9%) 0.070 ms/op
Iteration   1: 1.922 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.922 ms/op


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.095 ms/op
Iteration   1: 3.541 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.541 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.079 ms/op
Iteration   1: 2.060 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   1.896 ms/op
                 createUser·p0.90:   2.327 ms/op
                 createUser·p0.95:   2.596 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  24.609 ms/op
                 createUser·p0.9999: 25.174 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15524
  mean =      2.060 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14630 
    [ 2.500,  5.000) = 755 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 59 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.596 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =     24.609 ms/op
     p(99.9900) =     25.174 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.090 ms/op
Iteration   1: 1.787 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   1.741 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.367 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  16.009 ms/op
                 existUser·p0.9999: 16.138 ms/op
                 existUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17900
  mean =      1.787 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1211 
    [ 1.250,  2.500) = 16140 
    [ 2.500,  3.750) = 387 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.367 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =     16.009 ms/op
     p(99.9900) =     16.138 ms/op
     p(99.9990) =     16.138 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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
# Warmup Iteration   1: 3.311 ±(99.9%) 0.078 ms/op
Iteration   1: 2.041 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   1.917 ms/op
                 getUser·p0.90:   2.470 ms/op
                 getUser·p0.95:   2.814 ms/op
                 getUser·p0.99:   3.790 ms/op
                 getUser·p0.999:  18.022 ms/op
                 getUser·p0.9999: 19.192 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15674
  mean =      2.041 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 14155 
    [ 2.500,  3.750) = 1277 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 71 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      3.790 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     19.192 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.163 ms/op
Iteration   1: 3.146 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   2.798 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.196 ms/op
                 listUser·p0.999:  19.033 ms/op
                 listUser·p0.9999: 20.676 ms/op
                 listUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10157
  mean =      3.146 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2083 
    [ 2.500,  5.000) = 7844 
    [ 5.000,  7.500) = 171 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.196 ms/op
     p(99.9000) =     19.033 ms/op
     p(99.9900) =     20.676 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.923          ops/ms
ClientSimple.existUser                       thrpt         12.805          ops/ms
ClientSimple.getUser                         thrpt         11.660          ops/ms
ClientSimple.listUser                        thrpt          8.036          ops/ms
ClientSimple.createUser                       avgt          2.301           ms/op
ClientSimple.existUser                        avgt          1.994           ms/op
ClientSimple.getUser                          avgt          1.922           ms/op
ClientSimple.listUser                         avgt          3.541           ms/op
ClientSimple.createUser                     sample  15524   2.060 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.870           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.896           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.327           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.596           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.555           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.609           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.174           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.264           ms/op
ClientSimple.existUser                      sample  17900   1.787 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.583           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.741           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.183           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.543           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.009           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.138           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.138           ms/op
ClientSimple.getUser                        sample  15674   2.041 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.752           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.917           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.790           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.022           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.192           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.825           ms/op
ClientSimple.listUser                       sample  10157   3.146 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.120           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.798           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.125           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.196           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.033           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.676           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.677           ms/op

Benchmark result is saved to 1721090560782.json
