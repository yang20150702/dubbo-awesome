# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.154 ops/ms
Iteration   1: 2.163 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.163 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.304 ops/ms
Iteration   1: 4.727 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.727 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.544 ops/ms
Iteration   1: 3.973 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.973 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.926 ops/ms
Iteration   1: 1.203 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.203 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 15.365 ±(99.9%) 0.240 ms/op
Iteration   1: 7.329 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.329 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.700 ±(99.9%) 0.073 ms/op
Iteration   1: 4.196 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.196 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.556 ±(99.9%) 0.141 ms/op
Iteration   1: 4.142 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.142 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 27.361 ±(99.9%) 0.296 ms/op
Iteration   1: 18.399 ±(99.9%) 0.137 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.399 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.280 ±(99.9%) 0.471 ms/op
Iteration   1: 5.909 ±(99.9%) 0.142 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.660 ms/op
                 createUser·p0.95:   6.831 ms/op
                 createUser·p0.99:   25.198 ms/op
                 createUser·p0.999:  39.977 ms/op
                 createUser·p0.9999: 40.698 ms/op
                 createUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5601
  mean =      5.909 ±(99.9%) 0.142 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 984 
    [ 5.000, 10.000) = 4458 
    [10.000, 15.000) = 65 
    [15.000, 20.000) = 30 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.660 ms/op
     p(95.0000) =      6.831 ms/op
     p(99.0000) =     25.198 ms/op
     p(99.9000) =     39.977 ms/op
     p(99.9900) =     40.698 ms/op
     p(99.9990) =     40.698 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.085 ±(99.9%) 0.242 ms/op
Iteration   1: 4.897 ±(99.9%) 0.089 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   5.603 ms/op
                 existUser·p0.95:   5.997 ms/op
                 existUser·p0.99:   9.159 ms/op
                 existUser·p0.999:  31.864 ms/op
                 existUser·p0.9999: 32.080 ms/op
                 existUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6598
  mean =      4.897 ±(99.9%) 0.089 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 367 
    [ 2.500,  5.000) = 3393 
    [ 5.000,  7.500) = 2683 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     31.864 ms/op
     p(99.9900) =     32.080 ms/op
     p(99.9990) =     32.080 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.635 ±(99.9%) 0.361 ms/op
Iteration   1: 5.282 ±(99.9%) 0.056 ms/op
                 getUser·p0.00:   1.692 ms/op
                 getUser·p0.50:   5.071 ms/op
                 getUser·p0.90:   6.390 ms/op
                 getUser·p0.95:   7.176 ms/op
                 getUser·p0.99:   12.304 ms/op
                 getUser·p0.999:  14.581 ms/op
                 getUser·p0.9999: 14.615 ms/op
                 getUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6069
  mean =      5.282 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 17 
    [ 2.500,  3.750) = 129 
    [ 3.750,  5.000) = 2689 
    [ 5.000,  6.250) = 2561 
    [ 6.250,  7.500) = 440 
    [ 7.500,  8.750) = 129 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.692 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =     12.304 ms/op
     p(99.9000) =     14.581 ms/op
     p(99.9900) =     14.615 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.769 ±(99.9%) 0.835 ms/op
Iteration   1: 16.895 ±(99.9%) 0.263 ms/op
                 listUser·p0.00:   6.373 ms/op
                 listUser·p0.50:   17.531 ms/op
                 listUser·p0.90:   18.973 ms/op
                 listUser·p0.95:   21.807 ms/op
                 listUser·p0.99:   29.576 ms/op
                 listUser·p0.999:  36.380 ms/op
                 listUser·p0.9999: 36.438 ms/op
                 listUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1889
  mean =     16.895 ±(99.9%) 0.263 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 465 
    [15.000, 17.500) = 380 
    [17.500, 20.000) = 816 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      6.373 ms/op
     p(50.0000) =     17.531 ms/op
     p(90.0000) =     18.973 ms/op
     p(95.0000) =     21.807 ms/op
     p(99.0000) =     29.576 ms/op
     p(99.9000) =     36.380 ms/op
     p(99.9900) =     36.438 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.163          ops/ms
Client.existUser                       thrpt         4.727          ops/ms
Client.getUser                         thrpt         3.973          ops/ms
Client.listUser                        thrpt         1.203          ops/ms
Client.createUser                       avgt         7.329           ms/op
Client.existUser                        avgt         4.196           ms/op
Client.getUser                          avgt         4.142           ms/op
Client.listUser                         avgt        18.399           ms/op
Client.createUser                     sample  5601   5.909 ± 0.142   ms/op
Client.createUser:createUser·p0.00    sample         1.321           ms/op
Client.createUser:createUser·p0.50    sample         5.349           ms/op
Client.createUser:createUser·p0.90    sample         6.660           ms/op
Client.createUser:createUser·p0.95    sample         6.831           ms/op
Client.createUser:createUser·p0.99    sample        25.198           ms/op
Client.createUser:createUser·p0.999   sample        39.977           ms/op
Client.createUser:createUser·p0.9999  sample        40.698           ms/op
Client.createUser:createUser·p1.00    sample        40.698           ms/op
Client.existUser                      sample  6598   4.897 ± 0.089   ms/op
Client.existUser:existUser·p0.00      sample         0.939           ms/op
Client.existUser:existUser·p0.50      sample         4.907           ms/op
Client.existUser:existUser·p0.90      sample         5.603           ms/op
Client.existUser:existUser·p0.95      sample         5.997           ms/op
Client.existUser:existUser·p0.99      sample         9.159           ms/op
Client.existUser:existUser·p0.999     sample        31.864           ms/op
Client.existUser:existUser·p0.9999    sample        32.080           ms/op
Client.existUser:existUser·p1.00      sample        32.080           ms/op
Client.getUser                        sample  6069   5.282 ± 0.056   ms/op
Client.getUser:getUser·p0.00          sample         1.692           ms/op
Client.getUser:getUser·p0.50          sample         5.071           ms/op
Client.getUser:getUser·p0.90          sample         6.390           ms/op
Client.getUser:getUser·p0.95          sample         7.176           ms/op
Client.getUser:getUser·p0.99          sample        12.304           ms/op
Client.getUser:getUser·p0.999         sample        14.581           ms/op
Client.getUser:getUser·p0.9999        sample        14.615           ms/op
Client.getUser:getUser·p1.00          sample        14.615           ms/op
Client.listUser                       sample  1889  16.895 ± 0.263   ms/op
Client.listUser:listUser·p0.00        sample         6.373           ms/op
Client.listUser:listUser·p0.50        sample        17.531           ms/op
Client.listUser:listUser·p0.90        sample        18.973           ms/op
Client.listUser:listUser·p0.95        sample        21.807           ms/op
Client.listUser:listUser·p0.99        sample        29.576           ms/op
Client.listUser:listUser·p0.999       sample        36.380           ms/op
Client.listUser:listUser·p0.9999      sample        36.438           ms/op
Client.listUser:listUser·p1.00        sample        36.438           ms/op
