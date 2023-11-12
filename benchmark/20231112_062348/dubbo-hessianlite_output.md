# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.541 ops/ms
Iteration   1: 6.161 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.161 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.667 ops/ms
Iteration   1: 14.923 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.923 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.380 ops/ms
Iteration   1: 8.752 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.752 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.718 ops/ms
Iteration   1: 4.093 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.093 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ±(99.9%) 0.072 ms/op
Iteration   1: 2.822 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.822 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.108 ±(99.9%) 0.033 ms/op
Iteration   1: 2.385 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.385 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.118 ±(99.9%) 0.061 ms/op
Iteration   1: 3.131 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.131 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.653 ±(99.9%) 0.230 ms/op
Iteration   1: 8.791 ±(99.9%) 0.173 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.791 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.802 ±(99.9%) 0.104 ms/op
Iteration   1: 3.437 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   8.116 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 19.497 ms/op
                 createUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9330
  mean =      3.437 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 778 
    [ 2.500,  3.750) = 6086 
    [ 3.750,  5.000) = 2164 
    [ 5.000,  6.250) = 144 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      8.116 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.933 ±(99.9%) 0.053 ms/op
Iteration   1: 1.733 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.511 ms/op
                 existUser·p0.50:   1.599 ms/op
                 existUser·p0.90:   2.322 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   3.075 ms/op
                 existUser·p0.999:  13.207 ms/op
                 existUser·p0.9999: 13.732 ms/op
                 existUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18445
  mean =      1.733 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2091 
    [ 1.250,  2.500) = 15414 
    [ 2.500,  3.750) = 838 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.599 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.075 ms/op
     p(99.9000) =     13.207 ms/op
     p(99.9900) =     13.732 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ±(99.9%) 0.090 ms/op
Iteration   1: 2.831 ±(99.9%) 0.070 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   8.264 ms/op
                 getUser·p0.999:  41.812 ms/op
                 getUser·p0.9999: 44.023 ms/op
                 getUser·p1.00:   44.040 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11289
  mean =      2.831 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11047 
    [ 5.000, 10.000) = 135 
    [10.000, 15.000) = 57 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      8.264 ms/op
     p(99.9000) =     41.812 ms/op
     p(99.9900) =     44.023 ms/op
     p(99.9990) =     44.040 ms/op
     p(99.9999) =     44.040 ms/op
    p(100.0000) =     44.040 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.042 ±(99.9%) 0.332 ms/op
Iteration   1: 8.141 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   1.972 ms/op
                 listUser·p0.50:   7.873 ms/op
                 listUser·p0.90:   11.010 ms/op
                 listUser·p0.95:   12.321 ms/op
                 listUser·p0.99:   14.242 ms/op
                 listUser·p0.999:  16.159 ms/op
                 listUser·p0.9999: 32.047 ms/op
                 listUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3936
  mean =      8.141 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 148 
    [ 5.000,  7.500) = 1449 
    [ 7.500, 10.000) = 1631 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.972 ms/op
     p(50.0000) =      7.873 ms/op
     p(90.0000) =     11.010 ms/op
     p(95.0000) =     12.321 ms/op
     p(99.0000) =     14.242 ms/op
     p(99.9000) =     16.159 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.161          ops/ms
Client.existUser                       thrpt         14.923          ops/ms
Client.getUser                         thrpt          8.752          ops/ms
Client.listUser                        thrpt          4.093          ops/ms
Client.createUser                       avgt          2.822           ms/op
Client.existUser                        avgt          2.385           ms/op
Client.getUser                          avgt          3.131           ms/op
Client.listUser                         avgt          8.791           ms/op
Client.createUser                     sample   9330   3.437 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          0.815           ms/op
Client.createUser:createUser·p0.50    sample          3.178           ms/op
Client.createUser:createUser·p0.90    sample          4.375           ms/op
Client.createUser:createUser·p0.95    sample          4.719           ms/op
Client.createUser:createUser·p0.99    sample          8.116           ms/op
Client.createUser:createUser·p0.999   sample         19.300           ms/op
Client.createUser:createUser·p0.9999  sample         19.497           ms/op
Client.createUser:createUser·p1.00    sample         19.497           ms/op
Client.existUser                      sample  18445   1.733 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.511           ms/op
Client.existUser:existUser·p0.50      sample          1.599           ms/op
Client.existUser:existUser·p0.90      sample          2.322           ms/op
Client.existUser:existUser·p0.95      sample          2.507           ms/op
Client.existUser:existUser·p0.99      sample          3.075           ms/op
Client.existUser:existUser·p0.999     sample         13.207           ms/op
Client.existUser:existUser·p0.9999    sample         13.732           ms/op
Client.existUser:existUser·p1.00      sample         13.746           ms/op
Client.getUser                        sample  11289   2.831 ± 0.070   ms/op
Client.getUser:getUser·p0.00          sample          0.544           ms/op
Client.getUser:getUser·p0.50          sample          2.519           ms/op
Client.getUser:getUser·p0.90          sample          3.551           ms/op
Client.getUser:getUser·p0.95          sample          3.998           ms/op
Client.getUser:getUser·p0.99          sample          8.264           ms/op
Client.getUser:getUser·p0.999         sample         41.812           ms/op
Client.getUser:getUser·p0.9999        sample         44.023           ms/op
Client.getUser:getUser·p1.00          sample         44.040           ms/op
Client.listUser                       sample   3936   8.141 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample          1.972           ms/op
Client.listUser:listUser·p0.50        sample          7.873           ms/op
Client.listUser:listUser·p0.90        sample         11.010           ms/op
Client.listUser:listUser·p0.95        sample         12.321           ms/op
Client.listUser:listUser·p0.99        sample         14.242           ms/op
Client.listUser:listUser·p0.999       sample         16.159           ms/op
Client.listUser:listUser·p0.9999      sample         32.047           ms/op
Client.listUser:listUser·p1.00        sample         32.047           ms/op
