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
# Warmup Iteration   1: 1.546 ops/ms
Iteration   1: 6.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.968 ops/ms


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
# Warmup Iteration   1: 6.022 ops/ms
Iteration   1: 12.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.706 ops/ms


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
# Warmup Iteration   1: 5.870 ops/ms
Iteration   1: 13.035 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.035 ops/ms


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
# Warmup Iteration   1: 5.786 ops/ms
Iteration   1: 8.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.183 ops/ms


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
# Warmup Iteration   1: 3.745 ±(99.9%) 0.074 ms/op
Iteration   1: 2.136 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.136 ms/op


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
# Warmup Iteration   1: 3.512 ±(99.9%) 0.053 ms/op
Iteration   1: 2.072 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.072 ms/op


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
# Warmup Iteration   1: 3.304 ±(99.9%) 0.059 ms/op
Iteration   1: 1.775 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.775 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.105 ms/op
Iteration   1: 3.446 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.446 ms/op


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.079 ms/op
Iteration   1: 2.311 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.142 ms/op
                 createUser·p0.90:   2.753 ms/op
                 createUser·p0.95:   3.160 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  14.666 ms/op
                 createUser·p0.9999: 18.365 ms/op
                 createUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13851
  mean =      2.311 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 10893 
    [ 2.500,  3.750) = 2538 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      2.142 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      3.160 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     14.666 ms/op
     p(99.9900) =     18.365 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 2.998 ±(99.9%) 0.071 ms/op
Iteration   1: 1.856 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.322 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.035 ms/op
                 existUser·p0.999:  11.629 ms/op
                 existUser·p0.9999: 12.108 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17227
  mean =      1.856 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1396 
    [ 1.250,  2.500) = 14899 
    [ 2.500,  3.750) = 791 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.035 ms/op
     p(99.9000) =     11.629 ms/op
     p(99.9900) =     12.108 ms/op
     p(99.9990) =     12.452 ms/op
     p(99.9999) =     12.452 ms/op
    p(100.0000) =     12.452 ms/op


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
# Warmup Iteration   1: 3.321 ±(99.9%) 0.086 ms/op
Iteration   1: 2.238 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.455 ms/op
                 getUser·p0.50:   2.079 ms/op
                 getUser·p0.90:   2.765 ms/op
                 getUser·p0.95:   2.973 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  22.964 ms/op
                 getUser·p0.9999: 23.672 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14301
  mean =      2.238 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10964 
    [ 2.500,  5.000) = 3214 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      2.973 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     22.964 ms/op
     p(99.9900) =     23.672 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 4.429 ±(99.9%) 0.118 ms/op
Iteration   1: 3.720 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.418 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  9.138 ms/op
                 listUser·p0.9999: 10.027 ms/op
                 listUser·p1.00:   10.027 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8603
  mean =      3.720 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 19 
    [ 1.000,  2.000) = 60 
    [ 2.000,  3.000) = 1933 
    [ 3.000,  4.000) = 4078 
    [ 4.000,  5.000) = 1864 
    [ 5.000,  6.000) = 458 
    [ 6.000,  7.000) = 88 
    [ 7.000,  8.000) = 55 
    [ 8.000,  9.000) = 39 
    [ 9.000, 10.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =      9.138 ms/op
     p(99.9900) =     10.027 ms/op
     p(99.9990) =     10.027 ms/op
     p(99.9999) =     10.027 ms/op
    p(100.0000) =     10.027 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.968          ops/ms
ClientSimple.existUser                       thrpt         12.706          ops/ms
ClientSimple.getUser                         thrpt         13.035          ops/ms
ClientSimple.listUser                        thrpt          8.183          ops/ms
ClientSimple.createUser                       avgt          2.136           ms/op
ClientSimple.existUser                        avgt          2.072           ms/op
ClientSimple.getUser                          avgt          1.775           ms/op
ClientSimple.listUser                         avgt          3.446           ms/op
ClientSimple.createUser                     sample  13851   2.311 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.997           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.142           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.160           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.617           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.666           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.365           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.416           ms/op
ClientSimple.existUser                      sample  17227   1.856 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.455           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.835           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.035           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.629           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.108           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.452           ms/op
ClientSimple.getUser                        sample  14301   2.238 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.455           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.079           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.765           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.973           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.260           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.964           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.672           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.757           ms/op
ClientSimple.listUser                       sample   8603   3.720 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.418           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.715           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.292           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.586           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.138           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.027           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.027           ms/op

Benchmark result is saved to 1719576993131.json
