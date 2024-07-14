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
# Warmup Iteration   1: 1.036 ops/ms
Iteration   1: 6.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.481 ops/ms


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
# Warmup Iteration   1: 6.828 ops/ms
Iteration   1: 13.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.275 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.374 ops/ms
Iteration   1: 12.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.302 ops/ms


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
# Warmup Iteration   1: 4.714 ops/ms
Iteration   1: 9.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.889 ops/ms


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.067 ms/op
Iteration   1: 2.156 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.156 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.065 ms/op
Iteration   1: 1.792 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.792 ms/op


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
# Warmup Iteration   1: 3.390 ±(99.9%) 0.057 ms/op
Iteration   1: 2.261 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.261 ms/op


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.098 ms/op
Iteration   1: 3.396 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.396 ms/op


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.140 ms/op
Iteration   1: 2.047 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   1.767 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   2.793 ms/op
                 createUser·p0.99:   8.807 ms/op
                 createUser·p0.999:  15.254 ms/op
                 createUser·p0.9999: 16.441 ms/op
                 createUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16321
  mean =      2.047 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 366 
    [ 1.250,  2.500) = 13516 
    [ 2.500,  3.750) = 2088 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      8.807 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     16.441 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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
# Warmup Iteration   1: 2.704 ±(99.9%) 0.066 ms/op
Iteration   1: 2.153 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   2.150 ms/op
                 existUser·p0.90:   2.556 ms/op
                 existUser·p0.95:   2.671 ms/op
                 existUser·p0.99:   3.163 ms/op
                 existUser·p0.999:  28.017 ms/op
                 existUser·p0.9999: 28.262 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14986
  mean =      2.153 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12952 
    [ 2.500,  5.000) = 1981 
    [ 5.000,  7.500) = 21 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.150 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      3.163 ms/op
     p(99.9000) =     28.017 ms/op
     p(99.9900) =     28.262 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.073 ms/op
Iteration   1: 1.927 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.516 ms/op
                 getUser·p0.50:   1.800 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   2.744 ms/op
                 getUser·p0.99:   3.297 ms/op
                 getUser·p0.999:  12.442 ms/op
                 getUser·p0.9999: 12.698 ms/op
                 getUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16583
  mean =      1.927 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 371 
    [ 1.250,  2.500) = 14288 
    [ 2.500,  3.750) = 1805 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.297 ms/op
     p(99.9000) =     12.442 ms/op
     p(99.9900) =     12.698 ms/op
     p(99.9990) =     12.698 ms/op
     p(99.9999) =     12.698 ms/op
    p(100.0000) =     12.698 ms/op


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
# Warmup Iteration   1: 5.168 ±(99.9%) 0.300 ms/op
Iteration   1: 3.571 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   0.728 ms/op
                 listUser·p0.50:   3.301 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.426 ms/op
                 listUser·p0.999:  57.544 ms/op
                 listUser·p0.9999: 58.130 ms/op
                 listUser·p1.00:   58.130 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8951
  mean =      3.571 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8702 
    [ 5.000, 10.000) = 185 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 29 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.426 ms/op
     p(99.9000) =     57.544 ms/op
     p(99.9900) =     58.130 ms/op
     p(99.9990) =     58.130 ms/op
     p(99.9999) =     58.130 ms/op
    p(100.0000) =     58.130 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.481          ops/ms
ClientSimple.existUser                       thrpt         13.275          ops/ms
ClientSimple.getUser                         thrpt         12.302          ops/ms
ClientSimple.listUser                        thrpt          9.889          ops/ms
ClientSimple.createUser                       avgt          2.156           ms/op
ClientSimple.existUser                        avgt          1.792           ms/op
ClientSimple.getUser                          avgt          2.261           ms/op
ClientSimple.listUser                         avgt          3.396           ms/op
ClientSimple.createUser                     sample  16321   2.047 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.595           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.767           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.793           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.807           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.254           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.441           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.482           ms/op
ClientSimple.existUser                      sample  14986   2.153 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.573           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.671           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.163           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.017           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.262           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.279           ms/op
ClientSimple.getUser                        sample  16583   1.927 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.516           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.800           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.297           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.442           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.698           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.698           ms/op
ClientSimple.listUser                       sample   8951   3.571 ± 0.119   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.728           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.301           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.157           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.426           ms/op
ClientSimple.listUser:listUser·p0.999       sample         57.544           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         58.130           ms/op
ClientSimple.listUser:listUser·p1.00        sample         58.130           ms/op

Benchmark result is saved to 1720917992573.json
