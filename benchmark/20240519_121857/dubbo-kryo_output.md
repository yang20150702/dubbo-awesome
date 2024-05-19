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
# Warmup Iteration   1: 1.837 ops/ms
Iteration   1: 6.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.957 ops/ms


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
# Warmup Iteration   1: 6.377 ops/ms
Iteration   1: 14.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.043 ops/ms


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
# Warmup Iteration   1: 5.866 ops/ms
Iteration   1: 13.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.029 ops/ms


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
# Warmup Iteration   1: 5.766 ops/ms
Iteration   1: 8.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.254 ops/ms


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.068 ms/op
Iteration   1: 2.278 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.278 ms/op


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.057 ms/op
Iteration   1: 1.823 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.823 ms/op


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
# Warmup Iteration   1: 3.611 ±(99.9%) 0.138 ms/op
Iteration   1: 2.171 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.171 ms/op


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
# Warmup Iteration   1: 4.612 ±(99.9%) 0.088 ms/op
Iteration   1: 3.546 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.546 ms/op


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
# Warmup Iteration   1: 3.480 ±(99.9%) 0.085 ms/op
Iteration   1: 2.207 ±(99.9%) 0.075 ms/op
                 createUser·p0.00:   0.364 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.396 ms/op
                 createUser·p0.95:   2.674 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  47.075 ms/op
                 createUser·p0.9999: 53.024 ms/op
                 createUser·p1.00:   53.084 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14562
  mean =      2.207 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14317 
    [ 5.000, 10.000) = 149 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 15 
    [20.000, 25.000) = 17 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 21 
    [50.000, 55.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.364 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.674 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     47.075 ms/op
     p(99.9900) =     53.024 ms/op
     p(99.9990) =     53.084 ms/op
     p(99.9999) =     53.084 ms/op
    p(100.0000) =     53.084 ms/op


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
# Warmup Iteration   1: 3.200 ±(99.9%) 0.128 ms/op
Iteration   1: 1.995 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.195 ms/op
                 existUser·p0.50:   1.970 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.061 ms/op
                 existUser·p0.999:  9.952 ms/op
                 existUser·p0.9999: 10.627 ms/op
                 existUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16074
  mean =      1.995 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 429 
    [ 1.250,  2.500) = 13959 
    [ 2.500,  3.750) = 1576 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.195 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.061 ms/op
     p(99.9000) =      9.952 ms/op
     p(99.9900) =     10.627 ms/op
     p(99.9990) =     10.895 ms/op
     p(99.9999) =     10.895 ms/op
    p(100.0000) =     10.895 ms/op


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
# Warmup Iteration   1: 3.314 ±(99.9%) 0.074 ms/op
Iteration   1: 2.256 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.822 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  14.694 ms/op
                 getUser·p0.9999: 17.747 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14167
  mean =      2.256 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 239 
    [ 1.250,  2.500) = 10943 
    [ 2.500,  3.750) = 2723 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     14.694 ms/op
     p(99.9900) =     17.747 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.131 ms/op
Iteration   1: 3.094 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   2.761 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  20.644 ms/op
                 listUser·p0.9999: 20.741 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10339
  mean =      3.094 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3417 
    [ 2.500,  5.000) = 6653 
    [ 5.000,  7.500) = 166 
    [ 7.500, 10.000) = 70 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     20.741 ms/op
     p(99.9990) =     20.742 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.957          ops/ms
ClientSimple.existUser                       thrpt         14.043          ops/ms
ClientSimple.getUser                         thrpt         13.029          ops/ms
ClientSimple.listUser                        thrpt          8.254          ops/ms
ClientSimple.createUser                       avgt          2.278           ms/op
ClientSimple.existUser                        avgt          1.823           ms/op
ClientSimple.getUser                          avgt          2.171           ms/op
ClientSimple.listUser                         avgt          3.546           ms/op
ClientSimple.createUser                     sample  14562   2.207 ± 0.075   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.364           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.396           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.674           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.389           ms/op
ClientSimple.createUser:createUser·p0.999   sample         47.075           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         53.024           ms/op
ClientSimple.createUser:createUser·p1.00    sample         53.084           ms/op
ClientSimple.existUser                      sample  16074   1.995 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.195           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.970           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.061           ms/op
ClientSimple.existUser:existUser·p0.999     sample          9.952           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.627           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.895           ms/op
ClientSimple.getUser                        sample  14167   2.256 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.651           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.056           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.652           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.694           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.747           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.760           ms/op
ClientSimple.listUser                       sample  10339   3.094 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.270           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.761           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.961           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.684           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.644           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.741           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.742           ms/op

Benchmark result is saved to 1716120877973.json
