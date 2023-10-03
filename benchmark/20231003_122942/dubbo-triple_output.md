# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.304 ops/ms
# Warmup Iteration   2: 5.694 ops/ms
# Warmup Iteration   3: 9.459 ops/ms
Iteration   1: 9.859 ops/ms
Iteration   2: 9.766 ops/ms
Iteration   3: 9.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.804 ±(99.9%) 0.889 ops/ms [Average]
  (min, avg, max) = (9.766, 9.804, 9.859), stdev = 0.049
  CI (99.9%): [8.915, 10.692] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ops/ms
# Warmup Iteration   2: 9.420 ops/ms
# Warmup Iteration   3: 10.244 ops/ms
Iteration   1: 10.086 ops/ms
Iteration   2: 9.944 ops/ms
Iteration   3: 10.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.074 ±(99.9%) 2.257 ops/ms [Average]
  (min, avg, max) = (9.944, 10.074, 10.191), stdev = 0.124
  CI (99.9%): [7.817, 12.331] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.661 ops/ms
# Warmup Iteration   2: 9.123 ops/ms
# Warmup Iteration   3: 9.494 ops/ms
Iteration   1: 10.004 ops/ms
Iteration   2: 9.897 ops/ms
Iteration   3: 9.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.949 ±(99.9%) 0.977 ops/ms [Average]
  (min, avg, max) = (9.897, 9.949, 10.004), stdev = 0.054
  CI (99.9%): [8.972, 10.926] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.560 ops/ms
# Warmup Iteration   2: 7.834 ops/ms
# Warmup Iteration   3: 8.195 ops/ms
Iteration   1: 8.347 ops/ms
Iteration   2: 8.512 ops/ms
Iteration   3: 8.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.423 ±(99.9%) 1.521 ops/ms [Average]
  (min, avg, max) = (8.347, 8.423, 8.512), stdev = 0.083
  CI (99.9%): [6.902, 9.944] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.376 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.002 ms/op
Iteration   1: 3.284 ±(99.9%) 0.002 ms/op
Iteration   2: 3.292 ±(99.9%) 0.005 ms/op
Iteration   3: 3.231 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.269 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (3.231, 3.269, 3.292), stdev = 0.033
  CI (99.9%): [2.669, 3.869] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.461 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.002 ms/op
Iteration   1: 3.181 ±(99.9%) 0.005 ms/op
Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
Iteration   3: 3.079 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.131 ±(99.9%) 0.938 ms/op [Average]
  (min, avg, max) = (3.079, 3.131, 3.181), stdev = 0.051
  CI (99.9%): [2.193, 4.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.795 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.003 ms/op
Iteration   1: 3.225 ±(99.9%) 0.003 ms/op
Iteration   2: 3.207 ±(99.9%) 0.005 ms/op
Iteration   3: 3.212 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.215 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (3.207, 3.215, 3.225), stdev = 0.009
  CI (99.9%): [3.045, 3.384] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.061 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.003 ms/op
Iteration   1: 3.782 ±(99.9%) 0.004 ms/op
Iteration   2: 3.801 ±(99.9%) 0.005 ms/op
Iteration   3: 3.772 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.785 ±(99.9%) 0.267 ms/op [Average]
  (min, avg, max) = (3.772, 3.785, 3.801), stdev = 0.015
  CI (99.9%): [3.518, 4.052] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.574 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.009 ms/op
Iteration   1: 3.350 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  16.557 ms/op
                 createUser·p0.9999: 20.196 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.989 ms/op
                 createUser·p0.999:  8.071 ms/op
                 createUser·p0.9999: 20.646 ms/op
                 createUser·p1.00:   21.201 ms/op

Iteration   3: 3.307 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  17.060 ms/op
                 createUser·p0.9999: 19.115 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292114
  mean =      3.286 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15018 
    [ 2.500,  5.000) = 272474 
    [ 5.000,  7.500) = 3838 
    [ 7.500, 10.000) = 256 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 192 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     21.209 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.185 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.007 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  9.618 ms/op
                 existUser·p0.9999: 17.918 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 22.217 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  14.418 ms/op
                 existUser·p0.9999: 21.405 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300997
  mean =      3.187 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9719 
    [ 2.500,  5.000) = 285706 
    [ 5.000,  7.500) = 4714 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     21.394 ms/op
     p(99.9990) =     22.576 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.189 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.011 ms/op
Iteration   1: 3.184 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  12.607 ms/op
                 getUser·p0.9999: 18.676 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  13.820 ms/op
                 getUser·p0.9999: 20.414 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   3: 3.271 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  15.499 ms/op
                 getUser·p0.9999: 20.808 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299132
  mean =      3.208 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12979 
    [ 2.500,  5.000) = 281032 
    [ 5.000,  7.500) = 4265 
    [ 7.500, 10.000) = 317 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 169 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     13.891 ms/op
     p(99.9900) =     20.486 ms/op
     p(99.9990) =     21.234 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.830 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.009 ms/op
Iteration   1: 3.834 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 3.888 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.785 ms/op
                 listUser·p0.999:  13.684 ms/op
                 listUser·p0.9999: 16.053 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 3.742 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.601 ms/op
                 listUser·p0.999:  12.903 ms/op
                 listUser·p0.9999: 13.959 ms/op
                 listUser·p1.00:   14.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251283
  mean =      3.821 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 244635 
    [ 5.000,  7.500) = 4939 
    [ 7.500, 10.000) = 802 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 468 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     18.448 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.804 ± 0.889  ops/ms
ClientPb.existUser                       thrpt       3  10.074 ± 2.257  ops/ms
ClientPb.getUser                         thrpt       3   9.949 ± 0.977  ops/ms
ClientPb.listUser                        thrpt       3   8.423 ± 1.521  ops/ms
ClientPb.createUser                       avgt       3   3.269 ± 0.600   ms/op
ClientPb.existUser                        avgt       3   3.131 ± 0.938   ms/op
ClientPb.getUser                          avgt       3   3.215 ± 0.170   ms/op
ClientPb.listUser                         avgt       3   3.785 ± 0.267   ms/op
ClientPb.createUser                     sample  292114   3.286 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.208           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.744           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.251           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.332           ms/op
ClientPb.existUser                      sample  300997   3.187 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.652           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.394           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.610           ms/op
ClientPb.getUser                        sample  299132   3.208 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.204           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.543           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          20.486           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.627           ms/op
ClientPb.listUser                       sample  251283   3.821 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.582           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.448           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.120           ms/op
