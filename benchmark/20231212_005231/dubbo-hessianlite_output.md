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
# Warmup Iteration   1: 2.087 ops/ms
Iteration   1: 5.793 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.793 ops/ms


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
# Warmup Iteration   1: 6.122 ops/ms
Iteration   1: 13.286 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.286 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.216 ops/ms
Iteration   1: 8.640 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.640 ops/ms


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
# Warmup Iteration   1: 2.036 ops/ms
Iteration   1: 3.590 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.590 ops/ms


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
# Warmup Iteration   1: 5.425 ±(99.9%) 0.076 ms/op
Iteration   1: 3.173 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.173 ms/op


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
# Warmup Iteration   1: 3.159 ±(99.9%) 0.039 ms/op
Iteration   1: 1.884 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.884 ms/op


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
# Warmup Iteration   1: 4.498 ±(99.9%) 0.055 ms/op
Iteration   1: 2.690 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.690 ms/op


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
# Warmup Iteration   1: 12.507 ±(99.9%) 0.351 ms/op
Iteration   1: 9.061 ±(99.9%) 0.218 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.061 ms/op


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.094 ms/op
Iteration   1: 3.142 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.938 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   7.813 ms/op
                 createUser·p0.999:  15.225 ms/op
                 createUser·p0.9999: 15.319 ms/op
                 createUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10255
  mean =      3.142 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1742 
    [ 2.500,  3.750) = 7291 
    [ 3.750,  5.000) = 945 
    [ 5.000,  6.250) = 111 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.938 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.813 ms/op
     p(99.9000) =     15.225 ms/op
     p(99.9900) =     15.319 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.091 ms/op
Iteration   1: 1.861 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   1.811 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   3.032 ms/op
                 existUser·p0.999:  5.039 ms/op
                 existUser·p0.9999: 10.081 ms/op
                 existUser·p1.00:   10.093 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17182
  mean =      1.861 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 17 
    [ 1.000,  2.000) = 12957 
    [ 2.000,  3.000) = 4031 
    [ 3.000,  4.000) = 143 
    [ 4.000,  5.000) = 17 
    [ 5.000,  6.000) = 5 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      1.811 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.032 ms/op
     p(99.9000) =      5.039 ms/op
     p(99.9900) =     10.081 ms/op
     p(99.9990) =     10.093 ms/op
     p(99.9999) =     10.093 ms/op
    p(100.0000) =     10.093 ms/op


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.098 ms/op
Iteration   1: 3.153 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.974 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 9.809 ms/op
                 getUser·p1.00:   9.830 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10189
  mean =      3.153 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 470 
    [ 2.000,  3.000) = 4090 
    [ 3.000,  4.000) = 4319 
    [ 4.000,  5.000) = 1106 
    [ 5.000,  6.000) = 103 
    [ 6.000,  7.000) = 39 
    [ 7.000,  8.000) = 37 
    [ 8.000,  9.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.974 ms/op
     p(99.9000) =      8.602 ms/op
     p(99.9900) =      9.809 ms/op
     p(99.9990) =      9.830 ms/op
     p(99.9999) =      9.830 ms/op
    p(100.0000) =      9.830 ms/op


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
# Warmup Iteration   1: 12.551 ±(99.9%) 0.579 ms/op
Iteration   1: 7.957 ±(99.9%) 0.151 ms/op
                 listUser·p0.00:   3.199 ms/op
                 listUser·p0.50:   7.430 ms/op
                 listUser·p0.90:   10.066 ms/op
                 listUser·p0.95:   11.665 ms/op
                 listUser·p0.99:   22.421 ms/op
                 listUser·p0.999:  33.025 ms/op
                 listUser·p0.9999: 43.844 ms/op
                 listUser·p1.00:   43.844 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4015
  mean =      7.957 ±(99.9%) 0.151 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 142 
    [ 5.000, 10.000) = 3449 
    [10.000, 15.000) = 319 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 45 
    [25.000, 30.000) = 14 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.199 ms/op
     p(50.0000) =      7.430 ms/op
     p(90.0000) =     10.066 ms/op
     p(95.0000) =     11.665 ms/op
     p(99.0000) =     22.421 ms/op
     p(99.9000) =     33.025 ms/op
     p(99.9900) =     43.844 ms/op
     p(99.9990) =     43.844 ms/op
     p(99.9999) =     43.844 ms/op
    p(100.0000) =     43.844 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.793          ops/ms
Client.existUser                       thrpt         13.286          ops/ms
Client.getUser                         thrpt          8.640          ops/ms
Client.listUser                        thrpt          3.590          ops/ms
Client.createUser                       avgt          3.173           ms/op
Client.existUser                        avgt          1.884           ms/op
Client.getUser                          avgt          2.690           ms/op
Client.listUser                         avgt          9.061           ms/op
Client.createUser                     sample  10255   3.142 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          0.811           ms/op
Client.createUser:createUser·p0.50    sample          2.990           ms/op
Client.createUser:createUser·p0.90    sample          3.938           ms/op
Client.createUser:createUser·p0.95    sample          4.686           ms/op
Client.createUser:createUser·p0.99    sample          7.813           ms/op
Client.createUser:createUser·p0.999   sample         15.225           ms/op
Client.createUser:createUser·p0.9999  sample         15.319           ms/op
Client.createUser:createUser·p1.00    sample         15.319           ms/op
Client.existUser                      sample  17182   1.861 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.577           ms/op
Client.existUser:existUser·p0.50      sample          1.811           ms/op
Client.existUser:existUser·p0.90      sample          2.236           ms/op
Client.existUser:existUser·p0.95      sample          2.499           ms/op
Client.existUser:existUser·p0.99      sample          3.032           ms/op
Client.existUser:existUser·p0.999     sample          5.039           ms/op
Client.existUser:existUser·p0.9999    sample         10.081           ms/op
Client.existUser:existUser·p1.00      sample         10.093           ms/op
Client.getUser                        sample  10189   3.153 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          0.921           ms/op
Client.getUser:getUser·p0.50          sample          3.105           ms/op
Client.getUser:getUser·p0.90          sample          4.092           ms/op
Client.getUser:getUser·p0.95          sample          4.456           ms/op
Client.getUser:getUser·p0.99          sample          5.974           ms/op
Client.getUser:getUser·p0.999         sample          8.602           ms/op
Client.getUser:getUser·p0.9999        sample          9.809           ms/op
Client.getUser:getUser·p1.00          sample          9.830           ms/op
Client.listUser                       sample   4015   7.957 ± 0.151   ms/op
Client.listUser:listUser·p0.00        sample          3.199           ms/op
Client.listUser:listUser·p0.50        sample          7.430           ms/op
Client.listUser:listUser·p0.90        sample         10.066           ms/op
Client.listUser:listUser·p0.95        sample         11.665           ms/op
Client.listUser:listUser·p0.99        sample         22.421           ms/op
Client.listUser:listUser·p0.999       sample         33.025           ms/op
Client.listUser:listUser·p0.9999      sample         43.844           ms/op
Client.listUser:listUser·p1.00        sample         43.844           ms/op
