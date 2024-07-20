# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.852 ops/ms
Iteration   1: 8.064 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.064 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.303 ops/ms
Iteration   1: 12.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.202 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.864 ops/ms
Iteration   1: 13.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.438 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.882 ops/ms
Iteration   1: 8.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.632 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.267 ±(99.9%) 0.068 ms/op
Iteration   1: 2.613 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.613 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.230 ±(99.9%) 0.058 ms/op
Iteration   1: 1.840 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.840 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.604 ±(99.9%) 0.062 ms/op
Iteration   1: 2.255 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.255 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.563 ±(99.9%) 0.089 ms/op
Iteration   1: 3.817 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.666 ±(99.9%) 0.114 ms/op
Iteration   1: 2.159 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.453 ms/op
                 createUser·p0.50:   1.862 ms/op
                 createUser·p0.90:   2.757 ms/op
                 createUser·p0.95:   3.165 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  30.507 ms/op
                 createUser·p0.9999: 32.182 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14807
  mean =      2.159 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12208 
    [ 2.500,  5.000) = 2481 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.757 ms/op
     p(95.0000) =      3.165 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     30.507 ms/op
     p(99.9900) =     32.182 ms/op
     p(99.9990) =     32.276 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.974 ±(99.9%) 0.067 ms/op
Iteration   1: 1.961 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.725 ms/op
                 existUser·p0.99:   4.034 ms/op
                 existUser·p0.999:  14.476 ms/op
                 existUser·p0.9999: 16.212 ms/op
                 existUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16312
  mean =      1.961 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 502 
    [ 1.250,  2.500) = 14101 
    [ 2.500,  3.750) = 1512 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.725 ms/op
     p(99.0000) =      4.034 ms/op
     p(99.9000) =     14.476 ms/op
     p(99.9900) =     16.212 ms/op
     p(99.9990) =     16.253 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.576 ±(99.9%) 0.115 ms/op
Iteration   1: 2.603 ±(99.9%) 0.127 ms/op
                 getUser·p0.00:   0.523 ms/op
                 getUser·p0.50:   2.359 ms/op
                 getUser·p0.90:   2.867 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   6.047 ms/op
                 getUser·p0.999:  86.948 ms/op
                 getUser·p0.9999: 101.944 ms/op
                 getUser·p1.00:   101.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12292
  mean =      2.603 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 12237 
    [ 12.500,  25.000) = 9 
    [ 25.000,  37.500) = 7 
    [ 37.500,  50.000) = 7 
    [ 50.000,  62.500) = 7 
    [ 62.500,  75.000) = 7 
    [ 75.000,  87.500) = 7 
    [ 87.500, 100.000) = 7 
    [100.000, 112.500) = 4 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.359 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      6.047 ms/op
     p(99.9000) =     86.948 ms/op
     p(99.9900) =    101.944 ms/op
     p(99.9990) =    101.974 ms/op
     p(99.9999) =    101.974 ms/op
    p(100.0000) =    101.974 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.337 ±(99.9%) 0.116 ms/op
Iteration   1: 3.485 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.404 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.526 ms/op
                 listUser·p0.99:   7.321 ms/op
                 listUser·p0.999:  19.300 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9168
  mean =      3.485 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 588 
    [ 2.500,  3.750) = 5844 
    [ 3.750,  5.000) = 2512 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.526 ms/op
     p(99.0000) =      7.321 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     19.431 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           8.064          ops/ms
ClientSimple.existUser                       thrpt          12.202          ops/ms
ClientSimple.getUser                         thrpt          13.438          ops/ms
ClientSimple.listUser                        thrpt           8.632          ops/ms
ClientSimple.createUser                       avgt           2.613           ms/op
ClientSimple.existUser                        avgt           1.840           ms/op
ClientSimple.getUser                          avgt           2.255           ms/op
ClientSimple.listUser                         avgt           3.817           ms/op
ClientSimple.createUser                     sample  14807    2.159 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.453           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.862           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.757           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.165           ms/op
ClientSimple.createUser:createUser·p0.99    sample           4.448           ms/op
ClientSimple.createUser:createUser·p0.999   sample          30.507           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          32.182           ms/op
ClientSimple.createUser:createUser·p1.00    sample          32.276           ms/op
ClientSimple.existUser                      sample  16312    1.961 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.537           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.725           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.034           ms/op
ClientSimple.existUser:existUser·p0.999     sample          14.476           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          16.212           ms/op
ClientSimple.existUser:existUser·p1.00      sample          16.253           ms/op
ClientSimple.getUser                        sample  12292    2.603 ± 0.127   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.523           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.359           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.867           ms/op
ClientSimple.getUser:getUser·p0.95          sample           3.056           ms/op
ClientSimple.getUser:getUser·p0.99          sample           6.047           ms/op
ClientSimple.getUser:getUser·p0.999         sample          86.948           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         101.944           ms/op
ClientSimple.getUser:getUser·p1.00          sample         101.974           ms/op
ClientSimple.listUser                       sample   9168    3.485 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.009           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.404           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.526           ms/op
ClientSimple.listUser:listUser·p0.99        sample           7.321           ms/op
ClientSimple.listUser:listUser·p0.999       sample          19.300           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          19.431           ms/op
ClientSimple.listUser:listUser·p1.00        sample          19.431           ms/op

Benchmark result is saved to 1721477715379.json
