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
# Warmup Iteration   1: 1.720 ops/ms
Iteration   1: 6.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.093 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.590 ops/ms
Iteration   1: 12.252 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.252 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.897 ops/ms
Iteration   1: 13.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.616 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.832 ops/ms
Iteration   1: 7.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.837 ops/ms


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.086 ms/op
Iteration   1: 2.372 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.372 ms/op


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
# Warmup Iteration   1: 3.380 ±(99.9%) 0.051 ms/op
Iteration   1: 1.852 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.852 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.054 ms/op
Iteration   1: 1.752 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.752 ms/op


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
# Warmup Iteration   1: 5.430 ±(99.9%) 0.155 ms/op
Iteration   1: 3.888 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.888 ms/op


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.098 ms/op
Iteration   1: 2.358 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   2.083 ms/op
                 createUser·p0.90:   2.810 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   6.791 ms/op
                 createUser·p0.999:  30.048 ms/op
                 createUser·p0.9999: 31.771 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13701
  mean =      2.358 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11015 
    [ 2.500,  5.000) = 2441 
    [ 5.000,  7.500) = 120 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.281 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     30.048 ms/op
     p(99.9900) =     31.771 ms/op
     p(99.9990) =     32.244 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 3.272 ±(99.9%) 0.084 ms/op
Iteration   1: 1.859 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.398 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.719 ms/op
                 existUser·p0.99:   5.445 ms/op
                 existUser·p0.999:  14.221 ms/op
                 existUser·p0.9999: 14.448 ms/op
                 existUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17365
  mean =      1.859 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 460 
    [ 1.250,  2.500) = 15511 
    [ 2.500,  3.750) = 1066 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.719 ms/op
     p(99.0000) =      5.445 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     14.448 ms/op
     p(99.9990) =     14.533 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.107 ms/op
Iteration   1: 2.150 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   1.960 ms/op
                 getUser·p0.90:   2.761 ms/op
                 getUser·p0.95:   2.949 ms/op
                 getUser·p0.99:   4.074 ms/op
                 getUser·p0.999:  12.858 ms/op
                 getUser·p0.9999: 13.623 ms/op
                 getUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14884
  mean =      2.150 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 11722 
    [ 2.500,  3.750) = 2869 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      4.074 ms/op
     p(99.9000) =     12.858 ms/op
     p(99.9900) =     13.623 ms/op
     p(99.9990) =     13.631 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.131 ms/op
Iteration   1: 3.839 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  13.586 ms/op
                 listUser·p0.9999: 14.107 ms/op
                 listUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8338
  mean =      3.839 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 477 
    [ 2.500,  3.750) = 3531 
    [ 3.750,  5.000) = 3702 
    [ 5.000,  6.250) = 383 
    [ 6.250,  7.500) = 146 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     13.586 ms/op
     p(99.9900) =     14.107 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.093          ops/ms
ClientSimple.existUser                       thrpt         12.252          ops/ms
ClientSimple.getUser                         thrpt         13.616          ops/ms
ClientSimple.listUser                        thrpt          7.837          ops/ms
ClientSimple.createUser                       avgt          2.372           ms/op
ClientSimple.existUser                        avgt          1.852           ms/op
ClientSimple.getUser                          avgt          1.752           ms/op
ClientSimple.listUser                         avgt          3.888           ms/op
ClientSimple.createUser                     sample  13701   2.358 ± 0.056   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.660           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.083           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.281           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.791           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.048           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.771           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.244           ms/op
ClientSimple.existUser                      sample  17365   1.859 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.398           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.645           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.719           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.445           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.221           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.448           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.533           ms/op
ClientSimple.getUser                        sample  14884   2.150 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.670           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.960           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.761           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.074           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.858           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.623           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.631           ms/op
ClientSimple.listUser                       sample   8338   3.839 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.964           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.793           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.801           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.635           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.586           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.107           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.107           ms/op

Benchmark result is saved to 1715883069334.json
