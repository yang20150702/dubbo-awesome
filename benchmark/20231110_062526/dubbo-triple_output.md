# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.161 ops/ms
# Warmup Iteration   2: 4.841 ops/ms
# Warmup Iteration   3: 8.828 ops/ms
Iteration   1: 9.724 ops/ms
Iteration   2: 9.677 ops/ms
Iteration   3: 9.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.790 ±(99.9%) 2.867 ops/ms [Average]
  (min, avg, max) = (9.677, 9.790, 9.970), stdev = 0.157
  CI (99.9%): [6.923, 12.657] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.211 ops/ms
# Warmup Iteration   2: 9.161 ops/ms
# Warmup Iteration   3: 10.000 ops/ms
Iteration   1: 10.106 ops/ms
Iteration   2: 10.197 ops/ms
Iteration   3: 10.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.185 ±(99.9%) 1.337 ops/ms [Average]
  (min, avg, max) = (10.106, 10.185, 10.251), stdev = 0.073
  CI (99.9%): [8.848, 11.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.254 ops/ms
# Warmup Iteration   2: 8.783 ops/ms
# Warmup Iteration   3: 9.739 ops/ms
Iteration   1: 9.687 ops/ms
Iteration   2: 9.657 ops/ms
Iteration   3: 9.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.757 ±(99.9%) 2.722 ops/ms [Average]
  (min, avg, max) = (9.657, 9.757, 9.929), stdev = 0.149
  CI (99.9%): [7.035, 12.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ops/ms
# Warmup Iteration   2: 7.860 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 7.937 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.232 ±(99.9%) 4.667 ops/ms [Average]
  (min, avg, max) = (7.937, 8.232, 8.398), stdev = 0.256
  CI (99.9%): [3.565, 12.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.616 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.003 ms/op
Iteration   1: 3.189 ±(99.9%) 0.003 ms/op
Iteration   2: 3.337 ±(99.9%) 0.003 ms/op
Iteration   3: 3.280 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.269 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (3.189, 3.269, 3.337), stdev = 0.075
  CI (99.9%): [1.909, 4.629] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.494 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.003 ms/op
Iteration   1: 3.254 ±(99.9%) 0.004 ms/op
Iteration   2: 3.147 ±(99.9%) 0.004 ms/op
Iteration   3: 3.121 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.174 ±(99.9%) 1.283 ms/op [Average]
  (min, avg, max) = (3.121, 3.174, 3.254), stdev = 0.070
  CI (99.9%): [1.891, 4.457] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.822 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.002 ms/op
Iteration   1: 3.337 ±(99.9%) 0.003 ms/op
Iteration   2: 3.219 ±(99.9%) 0.003 ms/op
Iteration   3: 3.168 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.241 ±(99.9%) 1.583 ms/op [Average]
  (min, avg, max) = (3.168, 3.241, 3.337), stdev = 0.087
  CI (99.9%): [1.659, 4.824] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.626 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.004 ms/op
Iteration   1: 3.900 ±(99.9%) 0.005 ms/op
Iteration   2: 3.814 ±(99.9%) 0.007 ms/op
Iteration   3: 3.902 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.872 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.814, 3.872, 3.902), stdev = 0.051
  CI (99.9%): [2.950, 4.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.715 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.008 ms/op
Iteration   1: 3.254 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  17.400 ms/op
                 createUser·p0.9999: 19.470 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  15.300 ms/op
                 createUser·p0.9999: 21.430 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   3: 3.272 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  14.634 ms/op
                 createUser·p0.9999: 19.442 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293790
  mean =      3.266 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16040 
    [ 2.500,  5.000) = 272922 
    [ 5.000,  7.500) = 3839 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 189 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     15.002 ms/op
     p(99.9900) =     20.009 ms/op
     p(99.9990) =     21.631 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.439 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.009 ms/op
Iteration   1: 3.234 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 32.870 ms/op
                 existUser·p1.00:   33.227 ms/op

Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  14.874 ms/op
                 existUser·p0.9999: 23.568 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 3.212 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  11.976 ms/op
                 existUser·p0.9999: 22.908 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297674
  mean =      3.223 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16617 
    [ 2.500,  5.000) = 276296 
    [ 5.000,  7.500) = 3479 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.164 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     14.225 ms/op
     p(99.9900) =     31.367 ms/op
     p(99.9990) =     33.163 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.164 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.012 ms/op
Iteration   1: 3.239 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.579 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  14.558 ms/op
                 getUser·p0.9999: 21.987 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  10.538 ms/op
                 getUser·p0.9999: 22.643 ms/op
                 getUser·p1.00:   24.510 ms/op

Iteration   3: 3.289 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.128 ms/op
                 getUser·p0.999:  13.138 ms/op
                 getUser·p0.9999: 20.849 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295158
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12414 
    [ 2.500,  5.000) = 276637 
    [ 5.000,  7.500) = 5299 
    [ 7.500, 10.000) = 371 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 146 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     22.200 ms/op
     p(99.9990) =     23.021 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.228 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.970 ±(99.9%) 0.011 ms/op
Iteration   1: 3.903 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.912 ms/op
                 listUser·p0.9999: 22.433 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   2: 3.879 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.726 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.641 ms/op
                 listUser·p0.9999: 16.171 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   3: 3.898 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.064 ms/op
                 listUser·p0.9999: 16.580 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246432
  mean =      3.893 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 239629 
    [ 5.000,  7.500) = 5177 
    [ 7.500, 10.000) = 780 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 376 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.338 ms/op
     p(99.9900) =     20.503 ms/op
     p(99.9990) =     22.713 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.790 ± 2.867  ops/ms
ClientPb.existUser                       thrpt       3  10.185 ± 1.337  ops/ms
ClientPb.getUser                         thrpt       3   9.757 ± 2.722  ops/ms
ClientPb.listUser                        thrpt       3   8.232 ± 4.667  ops/ms
ClientPb.createUser                       avgt       3   3.269 ± 1.360   ms/op
ClientPb.existUser                        avgt       3   3.174 ± 1.283   ms/op
ClientPb.getUser                          avgt       3   3.241 ± 1.583   ms/op
ClientPb.listUser                         avgt       3   3.872 ± 0.922   ms/op
ClientPb.createUser                     sample  293790   3.266 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.188           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.002           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.009           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.692           ms/op
ClientPb.existUser                      sample  297674   3.223 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.805           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.164           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.743           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.225           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.367           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.227           ms/op
ClientPb.getUser                        sample  295158   3.255 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.049           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.451           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.200           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.510           ms/op
ClientPb.listUser                       sample  246432   3.893 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.726           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.764           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.338           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.503           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.905           ms/op
