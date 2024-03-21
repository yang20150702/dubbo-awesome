# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.903 ops/ms
Iteration   1: 6.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.826 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.555 ops/ms
Iteration   1: 12.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.208 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.606 ops/ms
Iteration   1: 12.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.400 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 3.329 ops/ms
Iteration   1: 8.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.645 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.927 ±(99.9%) 0.074 ms/op
Iteration   1: 2.022 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.022 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.147 ±(99.9%) 0.066 ms/op
Iteration   1: 1.929 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.929 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.172 ±(99.9%) 0.064 ms/op
Iteration   1: 2.011 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.011 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ±(99.9%) 0.109 ms/op
Iteration   1: 3.417 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.417 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.094 ms/op
Iteration   1: 2.481 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   2.302 ms/op
                 createUser·p0.90:   2.863 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   10.063 ms/op
                 createUser·p0.999:  25.035 ms/op
                 createUser·p0.9999: 25.517 ms/op
                 createUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12888
  mean =      2.481 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9057 
    [ 2.500,  5.000) = 3630 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.302 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =     10.063 ms/op
     p(99.9000) =     25.035 ms/op
     p(99.9900) =     25.517 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.113 ±(99.9%) 0.077 ms/op
Iteration   1: 1.880 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.515 ms/op
                 existUser·p0.99:   4.381 ms/op
                 existUser·p0.999:  13.335 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17017
  mean =      1.880 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 700 
    [ 1.250,  2.500) = 15452 
    [ 2.500,  3.750) = 630 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.484 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      4.381 ms/op
     p(99.9000) =     13.335 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     13.894 ms/op
     p(99.9999) =     13.894 ms/op
    p(100.0000) =     13.894 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.313 ±(99.9%) 0.090 ms/op
Iteration   1: 2.118 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.326 ms/op
                 getUser·p0.50:   1.948 ms/op
                 getUser·p0.90:   2.499 ms/op
                 getUser·p0.95:   2.724 ms/op
                 getUser·p0.99:   5.431 ms/op
                 getUser·p0.999:  36.176 ms/op
                 getUser·p0.9999: 36.569 ms/op
                 getUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15146
  mean =      2.118 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13643 
    [ 2.500,  5.000) = 1329 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     36.176 ms/op
     p(99.9900) =     36.569 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.775 ±(99.9%) 0.177 ms/op
Iteration   1: 3.440 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   0.836 ms/op
                 listUser·p0.50:   3.330 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.973 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9296
  mean =      3.440 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 275 
    [ 2.500,  3.750) = 6151 
    [ 3.750,  5.000) = 2704 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.162 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.973 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.826          ops/ms
ClientSimple.existUser                       thrpt         12.208          ops/ms
ClientSimple.getUser                         thrpt         12.400          ops/ms
ClientSimple.listUser                        thrpt          8.645          ops/ms
ClientSimple.createUser                       avgt          2.022           ms/op
ClientSimple.existUser                        avgt          1.929           ms/op
ClientSimple.getUser                          avgt          2.011           ms/op
ClientSimple.listUser                         avgt          3.417           ms/op
ClientSimple.createUser                     sample  12888   2.481 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.565           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.302           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.063           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.035           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.517           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.526           ms/op
ClientSimple.existUser                      sample  17017   1.880 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.484           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.515           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.381           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.335           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.779           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.894           ms/op
ClientSimple.getUser                        sample  15146   2.118 ± 0.046   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.326           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.948           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.499           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.431           ms/op
ClientSimple.getUser:getUser·p0.999         sample         36.176           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         36.569           ms/op
ClientSimple.getUser:getUser·p1.00          sample         36.569           ms/op
ClientSimple.listUser                       sample   9296   3.440 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.836           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.330           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.973           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.763           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.400           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.400           ms/op

Benchmark result is saved to 1711044636633.json
