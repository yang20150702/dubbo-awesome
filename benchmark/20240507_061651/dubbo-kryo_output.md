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
# Warmup Iteration   1: 1.439 ops/ms
Iteration   1: 7.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.084 ops/ms


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
# Warmup Iteration   1: 4.441 ops/ms
Iteration   1: 11.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.693 ops/ms


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
# Warmup Iteration   1: 5.477 ops/ms
Iteration   1: 13.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.512 ops/ms


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
# Warmup Iteration   1: 3.760 ops/ms
Iteration   1: 7.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.636 ops/ms


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.077 ms/op
Iteration   1: 2.222 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.222 ms/op


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
# Warmup Iteration   1: 3.330 ±(99.9%) 0.066 ms/op
Iteration   1: 1.657 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.657 ms/op


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
# Warmup Iteration   1: 3.226 ±(99.9%) 0.059 ms/op
Iteration   1: 2.298 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.298 ms/op


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
# Warmup Iteration   1: 5.033 ±(99.9%) 0.108 ms/op
Iteration   1: 3.235 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.235 ms/op


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
# Warmup Iteration   1: 3.380 ±(99.9%) 0.080 ms/op
Iteration   1: 2.166 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   2.001 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   2.732 ms/op
                 createUser·p0.99:   8.636 ms/op
                 createUser·p0.999:  23.066 ms/op
                 createUser·p0.9999: 29.599 ms/op
                 createUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14773
  mean =      2.166 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13066 
    [ 2.500,  5.000) = 1503 
    [ 5.000,  7.500) = 54 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      8.636 ms/op
     p(99.9000) =     23.066 ms/op
     p(99.9900) =     29.599 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 3.179 ±(99.9%) 0.080 ms/op
Iteration   1: 1.724 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   1.624 ms/op
                 existUser·p0.90:   1.982 ms/op
                 existUser·p0.95:   2.212 ms/op
                 existUser·p0.99:   2.964 ms/op
                 existUser·p0.999:  18.711 ms/op
                 existUser·p0.9999: 18.846 ms/op
                 existUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18545
  mean =      1.724 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 386 
    [ 1.250,  2.500) = 17719 
    [ 2.500,  3.750) = 332 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      1.624 ms/op
     p(90.0000) =      1.982 ms/op
     p(95.0000) =      2.212 ms/op
     p(99.0000) =      2.964 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     18.846 ms/op
     p(99.9990) =     18.874 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.139 ms/op
Iteration   1: 1.956 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.589 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   3.427 ms/op
                 getUser·p0.999:  5.213 ms/op
                 getUser·p0.9999: 7.275 ms/op
                 getUser·p1.00:   7.291 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16340
  mean =      1.956 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 41 
    [1.000, 1.500) = 2301 
    [1.500, 2.000) = 7423 
    [2.000, 2.500) = 4536 
    [2.500, 3.000) = 1600 
    [3.000, 3.500) = 320 
    [3.500, 4.000) = 48 
    [4.000, 4.500) = 24 
    [4.500, 5.000) = 11 
    [5.000, 5.500) = 26 
    [5.500, 6.000) = 7 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.427 ms/op
     p(99.9000) =      5.213 ms/op
     p(99.9900) =      7.275 ms/op
     p(99.9990) =      7.291 ms/op
     p(99.9999) =      7.291 ms/op
    p(100.0000) =      7.291 ms/op


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.148 ms/op
Iteration   1: 3.345 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.828 ms/op
                 listUser·p0.50:   3.256 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.335 ms/op
                 listUser·p0.999:  9.213 ms/op
                 listUser·p0.9999: 10.109 ms/op
                 listUser·p1.00:   10.109 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9669
  mean =      3.345 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 3 
    [ 1.000,  2.000) = 41 
    [ 2.000,  3.000) = 3934 
    [ 3.000,  4.000) = 4029 
    [ 4.000,  5.000) = 1277 
    [ 5.000,  6.000) = 241 
    [ 6.000,  7.000) = 74 
    [ 7.000,  8.000) = 40 
    [ 8.000,  9.000) = 18 
    [ 9.000, 10.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.335 ms/op
     p(99.9000) =      9.213 ms/op
     p(99.9900) =     10.109 ms/op
     p(99.9990) =     10.109 ms/op
     p(99.9999) =     10.109 ms/op
    p(100.0000) =     10.109 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.084          ops/ms
ClientSimple.existUser                       thrpt         11.693          ops/ms
ClientSimple.getUser                         thrpt         13.512          ops/ms
ClientSimple.listUser                        thrpt          7.636          ops/ms
ClientSimple.createUser                       avgt          2.222           ms/op
ClientSimple.existUser                        avgt          1.657           ms/op
ClientSimple.getUser                          avgt          2.298           ms/op
ClientSimple.listUser                         avgt          3.235           ms/op
ClientSimple.createUser                     sample  14773   2.166 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.447           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.001           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.732           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.636           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.066           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.599           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.147           ms/op
ClientSimple.existUser                      sample  18545   1.724 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.455           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.624           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.982           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.212           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.964           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.711           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.846           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.874           ms/op
ClientSimple.getUser                        sample  16340   1.956 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.584           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.589           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.427           ms/op
ClientSimple.getUser:getUser·p0.999         sample          5.213           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          7.275           ms/op
ClientSimple.getUser:getUser·p1.00          sample          7.291           ms/op
ClientSimple.listUser                       sample   9669   3.345 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.828           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.256           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.335           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.213           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.109           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.109           ms/op

Benchmark result is saved to 1715062349528.json
