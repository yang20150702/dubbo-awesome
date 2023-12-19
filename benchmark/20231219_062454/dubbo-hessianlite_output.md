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
# Warmup Iteration   1: 2.362 ops/ms
Iteration   1: 5.896 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.896 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.769 ops/ms
Iteration   1: 12.566 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.566 ops/ms


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
# Warmup Iteration   1: 3.744 ops/ms
Iteration   1: 7.766 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.766 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.141 ops/ms
Iteration   1: 3.350 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.350 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.434 ±(99.9%) 0.085 ms/op
Iteration   1: 3.210 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.210 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.146 ±(99.9%) 0.028 ms/op
Iteration   1: 1.940 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.940 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.829 ±(99.9%) 0.132 ms/op
Iteration   1: 2.948 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.948 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.931 ±(99.9%) 0.276 ms/op
Iteration   1: 8.490 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.490 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.960 ±(99.9%) 0.124 ms/op
Iteration   1: 2.892 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.712 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   4.327 ms/op
                 createUser·p0.99:   6.789 ms/op
                 createUser·p0.999:  15.221 ms/op
                 createUser·p0.9999: 17.353 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11035
  mean =      2.892 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 2387 
    [ 2.500,  3.750) = 7848 
    [ 3.750,  5.000) = 522 
    [ 5.000,  6.250) = 129 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      2.712 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      4.327 ms/op
     p(99.0000) =      6.789 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     17.353 ms/op
     p(99.9990) =     17.367 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.190 ±(99.9%) 0.080 ms/op
Iteration   1: 2.031 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.481 ms/op
                 existUser·p0.50:   1.995 ms/op
                 existUser·p0.90:   2.548 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   3.388 ms/op
                 existUser·p0.999:  6.025 ms/op
                 existUser·p0.9999: 10.237 ms/op
                 existUser·p1.00:   10.256 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15775
  mean =      2.031 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 40 
    [ 1.000,  2.000) = 7923 
    [ 2.000,  3.000) = 7429 
    [ 3.000,  4.000) = 282 
    [ 4.000,  5.000) = 6 
    [ 5.000,  6.000) = 75 
    [ 6.000,  7.000) = 16 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.388 ms/op
     p(99.9000) =      6.025 ms/op
     p(99.9900) =     10.237 ms/op
     p(99.9990) =     10.256 ms/op
     p(99.9999) =     10.256 ms/op
    p(100.0000) =     10.256 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ±(99.9%) 0.173 ms/op
Iteration   1: 2.927 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   2.724 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   6.379 ms/op
                 getUser·p0.999:  12.538 ms/op
                 getUser·p0.9999: 15.639 ms/op
                 getUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10914
  mean =      2.927 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 3943 
    [ 2.500,  3.750) = 5872 
    [ 3.750,  5.000) = 833 
    [ 5.000,  6.250) = 141 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.724 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.379 ms/op
     p(99.9000) =     12.538 ms/op
     p(99.9900) =     15.639 ms/op
     p(99.9990) =     15.712 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.505 ±(99.9%) 0.380 ms/op
Iteration   1: 7.892 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   7.520 ms/op
                 listUser·p0.90:   10.355 ms/op
                 listUser·p0.95:   11.338 ms/op
                 listUser·p0.99:   18.645 ms/op
                 listUser·p0.999:  23.765 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4049
  mean =      7.892 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 144 
    [ 5.000,  7.500) = 1869 
    [ 7.500, 10.000) = 1545 
    [10.000, 12.500) = 397 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.572 ms/op
     p(50.0000) =      7.520 ms/op
     p(90.0000) =     10.355 ms/op
     p(95.0000) =     11.338 ms/op
     p(99.0000) =     18.645 ms/op
     p(99.9000) =     23.765 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.896          ops/ms
Client.existUser                       thrpt         12.566          ops/ms
Client.getUser                         thrpt          7.766          ops/ms
Client.listUser                        thrpt          3.350          ops/ms
Client.createUser                       avgt          3.210           ms/op
Client.existUser                        avgt          1.940           ms/op
Client.getUser                          avgt          2.948           ms/op
Client.listUser                         avgt          8.490           ms/op
Client.createUser                     sample  11035   2.892 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          0.977           ms/op
Client.createUser:createUser·p0.50    sample          2.712           ms/op
Client.createUser:createUser·p0.90    sample          3.428           ms/op
Client.createUser:createUser·p0.95    sample          4.327           ms/op
Client.createUser:createUser·p0.99    sample          6.789           ms/op
Client.createUser:createUser·p0.999   sample         15.221           ms/op
Client.createUser:createUser·p0.9999  sample         17.353           ms/op
Client.createUser:createUser·p1.00    sample         17.367           ms/op
Client.existUser                      sample  15775   2.031 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.481           ms/op
Client.existUser:existUser·p0.50      sample          1.995           ms/op
Client.existUser:existUser·p0.90      sample          2.548           ms/op
Client.existUser:existUser·p0.95      sample          2.789           ms/op
Client.existUser:existUser·p0.99      sample          3.388           ms/op
Client.existUser:existUser·p0.999     sample          6.025           ms/op
Client.existUser:existUser·p0.9999    sample         10.237           ms/op
Client.existUser:existUser·p1.00      sample         10.256           ms/op
Client.getUser                        sample  10914   2.927 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          0.690           ms/op
Client.getUser:getUser·p0.50          sample          2.724           ms/op
Client.getUser:getUser·p0.90          sample          3.752           ms/op
Client.getUser:getUser·p0.95          sample          4.125           ms/op
Client.getUser:getUser·p0.99          sample          6.379           ms/op
Client.getUser:getUser·p0.999         sample         12.538           ms/op
Client.getUser:getUser·p0.9999        sample         15.639           ms/op
Client.getUser:getUser·p1.00          sample         15.712           ms/op
Client.listUser                       sample   4049   7.892 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          2.572           ms/op
Client.listUser:listUser·p0.50        sample          7.520           ms/op
Client.listUser:listUser·p0.90        sample         10.355           ms/op
Client.listUser:listUser·p0.95        sample         11.338           ms/op
Client.listUser:listUser·p0.99        sample         18.645           ms/op
Client.listUser:listUser·p0.999       sample         23.765           ms/op
Client.listUser:listUser·p0.9999      sample         24.150           ms/op
Client.listUser:listUser·p1.00        sample         24.150           ms/op
