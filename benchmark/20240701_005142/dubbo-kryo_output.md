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
# Warmup Iteration   1: 1.809 ops/ms
Iteration   1: 7.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.394 ops/ms


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
# Warmup Iteration   1: 5.531 ops/ms
Iteration   1: 11.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.780 ops/ms


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
# Warmup Iteration   1: 5.036 ops/ms
Iteration   1: 12.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.333 ops/ms


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
# Warmup Iteration   1: 4.292 ops/ms
Iteration   1: 8.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.861 ops/ms


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.101 ms/op
Iteration   1: 2.202 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.202 ms/op


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
# Warmup Iteration   1: 3.278 ±(99.9%) 0.063 ms/op
Iteration   1: 1.947 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.947 ms/op


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
# Warmup Iteration   1: 3.407 ±(99.9%) 0.061 ms/op
Iteration   1: 2.108 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.067 ±(99.9%) 0.136 ms/op
Iteration   1: 3.820 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.820 ms/op


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.096 ms/op
Iteration   1: 2.314 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   2.048 ms/op
                 createUser·p0.90:   2.875 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   11.005 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 21.834 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13815
  mean =      2.314 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10405 
    [ 2.500,  5.000) = 3072 
    [ 5.000,  7.500) = 171 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =     11.005 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     21.834 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 3.037 ±(99.9%) 0.075 ms/op
Iteration   1: 1.901 ±(99.9%) 0.059 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   1.589 ms/op
                 existUser·p0.90:   2.442 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  56.099 ms/op
                 existUser·p0.9999: 57.703 ms/op
                 existUser·p1.00:   58.065 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16898
  mean =      1.901 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16790 
    [ 5.000, 10.000) = 36 
    [10.000, 15.000) = 35 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      1.589 ms/op
     p(90.0000) =      2.442 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =     56.099 ms/op
     p(99.9900) =     57.703 ms/op
     p(99.9990) =     58.065 ms/op
     p(99.9999) =     58.065 ms/op
    p(100.0000) =     58.065 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.088 ms/op
Iteration   1: 2.242 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.130 ms/op
                 getUser·p0.90:   2.753 ms/op
                 getUser·p0.95:   2.896 ms/op
                 getUser·p0.99:   3.990 ms/op
                 getUser·p0.999:  19.030 ms/op
                 getUser·p0.9999: 19.427 ms/op
                 getUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14258
  mean =      2.242 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 10998 
    [ 2.500,  3.750) = 3022 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      3.990 ms/op
     p(99.9000) =     19.030 ms/op
     p(99.9900) =     19.427 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.136 ms/op
Iteration   1: 3.548 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.387 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.185 ms/op
                 listUser·p0.999:  10.093 ms/op
                 listUser·p0.9999: 10.387 ms/op
                 listUser·p1.00:   10.387 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9004
  mean =      3.548 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 67 
    [ 2.000,  3.000) = 2263 
    [ 3.000,  4.000) = 4887 
    [ 4.000,  5.000) = 1473 
    [ 5.000,  6.000) = 172 
    [ 6.000,  7.000) = 96 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 5 
    [ 9.000, 10.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.387 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     10.387 ms/op
     p(99.9990) =     10.387 ms/op
     p(99.9999) =     10.387 ms/op
    p(100.0000) =     10.387 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.394          ops/ms
ClientSimple.existUser                       thrpt         11.780          ops/ms
ClientSimple.getUser                         thrpt         12.333          ops/ms
ClientSimple.listUser                        thrpt          8.861          ops/ms
ClientSimple.createUser                       avgt          2.202           ms/op
ClientSimple.existUser                        avgt          1.947           ms/op
ClientSimple.getUser                          avgt          2.108           ms/op
ClientSimple.listUser                         avgt          3.820           ms/op
ClientSimple.createUser                     sample  13815   2.314 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.552           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.048           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.875           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.219           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.005           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.742           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.834           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.184           ms/op
ClientSimple.existUser                      sample  16898   1.901 ± 0.059   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.522           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.589           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.442           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.227           ms/op
ClientSimple.existUser:existUser·p0.999     sample         56.099           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         57.703           ms/op
ClientSimple.existUser:existUser·p1.00      sample         58.065           ms/op
ClientSimple.getUser                        sample  14258   2.242 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.943           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.130           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.990           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.030           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.427           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.497           ms/op
ClientSimple.listUser                       sample   9004   3.548 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.964           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.559           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.387           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.185           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.093           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.387           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.387           ms/op

Benchmark result is saved to 1719794833087.json
