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
# Warmup Iteration   1: 1.933 ops/ms
Iteration   1: 7.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.160 ops/ms


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
# Warmup Iteration   1: 6.228 ops/ms
Iteration   1: 12.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.964 ops/ms


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
# Warmup Iteration   1: 6.880 ops/ms
Iteration   1: 15.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.202 ops/ms


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
# Warmup Iteration   1: 5.111 ops/ms
Iteration   1: 8.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.736 ops/ms


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.061 ms/op
Iteration   1: 2.241 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.241 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.049 ms/op
Iteration   1: 1.797 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.797 ms/op


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
# Warmup Iteration   1: 3.511 ±(99.9%) 0.068 ms/op
Iteration   1: 2.260 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.260 ms/op


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
# Warmup Iteration   1: 4.439 ±(99.9%) 0.119 ms/op
Iteration   1: 3.659 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.659 ms/op


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
# Warmup Iteration   1: 3.707 ±(99.9%) 0.093 ms/op
Iteration   1: 2.095 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   1.925 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.732 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  21.642 ms/op
                 createUser·p0.9999: 23.096 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15255
  mean =      2.095 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13623 
    [ 2.500,  5.000) = 1463 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      1.925 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     21.642 ms/op
     p(99.9900) =     23.096 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.074 ms/op
Iteration   1: 1.797 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   1.556 ms/op
                 existUser·p0.90:   2.552 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   3.208 ms/op
                 existUser·p0.999:  15.398 ms/op
                 existUser·p0.9999: 15.896 ms/op
                 existUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17770
  mean =      1.797 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2401 
    [ 1.250,  2.500) = 13229 
    [ 2.500,  3.750) = 2062 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      1.556 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.208 ms/op
     p(99.9000) =     15.398 ms/op
     p(99.9900) =     15.896 ms/op
     p(99.9990) =     15.909 ms/op
     p(99.9999) =     15.909 ms/op
    p(100.0000) =     15.909 ms/op


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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.074 ms/op
Iteration   1: 2.117 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.634 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.966 ms/op
                 getUser·p0.99:   5.231 ms/op
                 getUser·p0.999:  17.982 ms/op
                 getUser·p0.9999: 19.269 ms/op
                 getUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15244
  mean =      2.117 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 241 
    [ 1.250,  2.500) = 12900 
    [ 2.500,  3.750) = 1784 
    [ 3.750,  5.000) = 137 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      5.231 ms/op
     p(99.9000) =     17.982 ms/op
     p(99.9900) =     19.269 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.120 ms/op
Iteration   1: 3.770 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  7.331 ms/op
                 listUser·p0.9999: 8.454 ms/op
                 listUser·p1.00:   8.454 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8510
  mean =      3.770 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 6 
    [1.500, 2.000) = 77 
    [2.000, 2.500) = 347 
    [2.500, 3.000) = 461 
    [3.000, 3.500) = 1512 
    [3.500, 4.000) = 3265 
    [4.000, 4.500) = 1956 
    [4.500, 5.000) = 638 
    [5.000, 5.500) = 154 
    [5.500, 6.000) = 52 
    [6.000, 6.500) = 17 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 13 
    [7.500, 8.000) = 3 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      7.331 ms/op
     p(99.9900) =      8.454 ms/op
     p(99.9990) =      8.454 ms/op
     p(99.9999) =      8.454 ms/op
    p(100.0000) =      8.454 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.160          ops/ms
ClientSimple.existUser                       thrpt         12.964          ops/ms
ClientSimple.getUser                         thrpt         15.202          ops/ms
ClientSimple.listUser                        thrpt          8.736          ops/ms
ClientSimple.createUser                       avgt          2.241           ms/op
ClientSimple.existUser                        avgt          1.797           ms/op
ClientSimple.getUser                          avgt          2.260           ms/op
ClientSimple.listUser                         avgt          3.659           ms/op
ClientSimple.createUser                     sample  15255   2.095 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.962           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.925           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.792           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.642           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.096           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.200           ms/op
ClientSimple.existUser                      sample  17770   1.797 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.773           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.556           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.552           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.208           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.398           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.896           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.909           ms/op
ClientSimple.getUser                        sample  15244   2.117 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.634           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.231           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.982           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.269           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.595           ms/op
ClientSimple.listUser                       sample   8510   3.770 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.868           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.777           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.538           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.331           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.454           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.454           ms/op

Benchmark result is saved to 1720354512688.json
