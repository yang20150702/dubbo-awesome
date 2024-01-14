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
# Warmup Iteration   1: 2.528 ops/ms
Iteration   1: 6.676 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.676 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.478 ops/ms
Iteration   1: 11.566 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.566 ops/ms


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
# Warmup Iteration   1: 4.681 ops/ms
Iteration   1: 9.207 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.207 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.485 ops/ms
Iteration   1: 3.456 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.456 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 4.979 ±(99.9%) 0.063 ms/op
Iteration   1: 3.111 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.111 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.229 ±(99.9%) 0.034 ms/op
Iteration   1: 1.865 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.865 ms/op


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
# Warmup Iteration   1: 4.744 ±(99.9%) 0.050 ms/op
Iteration   1: 2.825 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.825 ms/op


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
# Warmup Iteration   1: 11.429 ±(99.9%) 0.158 ms/op
Iteration   1: 7.356 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.356 ms/op


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
# Warmup Iteration   1: 5.021 ±(99.9%) 0.105 ms/op
Iteration   1: 3.324 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.821 ms/op
                 createUser·p0.95:   4.206 ms/op
                 createUser·p0.99:   9.829 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9650
  mean =      3.324 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 567 
    [ 2.500,  5.000) = 8875 
    [ 5.000,  7.500) = 109 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.821 ms/op
     p(95.0000) =      4.206 ms/op
     p(99.0000) =      9.829 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 3.160 ±(99.9%) 0.121 ms/op
Iteration   1: 1.796 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.394 ms/op
                 existUser·p0.50:   1.673 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   3.138 ms/op
                 existUser·p0.999:  5.644 ms/op
                 existUser·p0.9999: 6.219 ms/op
                 existUser·p1.00:   6.259 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18060
  mean =      1.796 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 6 
    [0.500, 1.000) = 228 
    [1.000, 1.500) = 5383 
    [1.500, 2.000) = 7839 
    [2.000, 2.500) = 2774 
    [2.500, 3.000) = 1558 
    [3.000, 3.500) = 148 
    [3.500, 4.000) = 27 
    [4.000, 4.500) = 1 
    [4.500, 5.000) = 25 
    [5.000, 5.500) = 42 
    [5.500, 6.000) = 21 
    [6.000, 6.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.394 ms/op
     p(50.0000) =      1.673 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.138 ms/op
     p(99.9000) =      5.644 ms/op
     p(99.9900) =      6.219 ms/op
     p(99.9990) =      6.259 ms/op
     p(99.9999) =      6.259 ms/op
    p(100.0000) =      6.259 ms/op


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
# Warmup Iteration   1: 4.640 ±(99.9%) 0.106 ms/op
Iteration   1: 3.103 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.332 ms/op
                 getUser·p0.99:   6.958 ms/op
                 getUser·p0.999:  16.613 ms/op
                 getUser·p0.9999: 18.313 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10362
  mean =      3.103 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 2454 
    [ 2.500,  3.750) = 6535 
    [ 3.750,  5.000) = 1051 
    [ 5.000,  6.250) = 171 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.332 ms/op
     p(99.0000) =      6.958 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     18.313 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 13.271 ±(99.9%) 0.545 ms/op
Iteration   1: 7.913 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   7.397 ms/op
                 listUser·p0.90:   10.781 ms/op
                 listUser·p0.95:   12.018 ms/op
                 listUser·p0.99:   18.809 ms/op
                 listUser·p0.999:  22.296 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4029
  mean =      7.913 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 161 
    [ 5.000,  7.500) = 1944 
    [ 7.500, 10.000) = 1370 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      7.397 ms/op
     p(90.0000) =     10.781 ms/op
     p(95.0000) =     12.018 ms/op
     p(99.0000) =     18.809 ms/op
     p(99.9000) =     22.296 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.676          ops/ms
Client.existUser                       thrpt         11.566          ops/ms
Client.getUser                         thrpt          9.207          ops/ms
Client.listUser                        thrpt          3.456          ops/ms
Client.createUser                       avgt          3.111           ms/op
Client.existUser                        avgt          1.865           ms/op
Client.getUser                          avgt          2.825           ms/op
Client.listUser                         avgt          7.356           ms/op
Client.createUser                     sample   9650   3.324 ± 0.048   ms/op
Client.createUser:createUser·p0.00    sample          0.585           ms/op
Client.createUser:createUser·p0.50    sample          3.125           ms/op
Client.createUser:createUser·p0.90    sample          3.821           ms/op
Client.createUser:createUser·p0.95    sample          4.206           ms/op
Client.createUser:createUser·p0.99    sample          9.829           ms/op
Client.createUser:createUser·p0.999   sample         20.742           ms/op
Client.createUser:createUser·p0.9999  sample         20.840           ms/op
Client.createUser:createUser·p1.00    sample         20.840           ms/op
Client.existUser                      sample  18060   1.796 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.394           ms/op
Client.existUser:existUser·p0.50      sample          1.673           ms/op
Client.existUser:existUser·p0.90      sample          2.507           ms/op
Client.existUser:existUser·p0.95      sample          2.703           ms/op
Client.existUser:existUser·p0.99      sample          3.138           ms/op
Client.existUser:existUser·p0.999     sample          5.644           ms/op
Client.existUser:existUser·p0.9999    sample          6.219           ms/op
Client.existUser:existUser·p1.00      sample          6.259           ms/op
Client.getUser                        sample  10362   3.103 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.933           ms/op
Client.getUser:getUser·p0.50          sample          3.015           ms/op
Client.getUser:getUser·p0.90          sample          3.858           ms/op
Client.getUser:getUser·p0.95          sample          4.332           ms/op
Client.getUser:getUser·p0.99          sample          6.958           ms/op
Client.getUser:getUser·p0.999         sample         16.613           ms/op
Client.getUser:getUser·p0.9999        sample         18.313           ms/op
Client.getUser:getUser·p1.00          sample         18.317           ms/op
Client.listUser                       sample   4029   7.913 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          2.097           ms/op
Client.listUser:listUser·p0.50        sample          7.397           ms/op
Client.listUser:listUser·p0.90        sample         10.781           ms/op
Client.listUser:listUser·p0.95        sample         12.018           ms/op
Client.listUser:listUser·p0.99        sample         18.809           ms/op
Client.listUser:listUser·p0.999       sample         22.296           ms/op
Client.listUser:listUser·p0.9999      sample         23.658           ms/op
Client.listUser:listUser·p1.00        sample         23.658           ms/op
